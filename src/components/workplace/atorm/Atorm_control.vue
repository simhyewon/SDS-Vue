<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery atorm">

        <!-- header 2단형 -->
        <div id="header" class="mainType2">
            <div class="header_inner line1">
                <button type="button" class="btn allMenu" @click="toggleDrawer()"><span class="ico">전체메뉴</span><span class="ico new"></span></button>  
                <p class="main_tit_txt">ATORM</p>          
                <button type="button" class="btn btnHome" @click="onClick(1)"><span class="ico">홈</span></button>
            </div>            
            <div class="header_inner line2">
                <ul class="gnbMenu text">
                    <li class="menu menu_product" :class="{'on': tabIdx == 2}"   @click="onClick(2)">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <span class="icon_desc">과정제작</span>
                    </li>
                    <li class="menu menu_process" :class="{'on': tabIdx == 3}"   @click="onClick(3)">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <span class="icon_desc">제작중</span>
                    </li>
                    <li class="menu menu_status" :class="{'on': tabIdx == 4}"   @click="onClick(4)">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <span class="icon_desc">과정운영관리</span>
                    </li>
                </ul>
            </div>
        </div>


        <div id="content" class="list">
          <div class="cell">
            <div class="inner">
                <component :is="component"/>
            </div>
          </div>
        </div>
      </div>
      <!-- //container -->    

      <!-- Drawer  아코디언 디자인 나오면 추가해야함 -->
      <div id="drawer" :class="{'show': drawerFlag }">
        <div class="drawer_inner">
          <div class="drawer_header">
            <div class="logo">
              <img src="@/assets/img/login_logo_sds.png" alt="samsung sds">
            </div>
            <div class="arm">
              <span class="new"></span>
              <span class="icon"></span>
            </div>
            <div class="setting">
              <span class="icon"></span>
            </div>
          </div>
          <ul class="drawer_list">
            <li class="open" @click="toggleMenu($event)">
              <a href="#">신규 아이템 추가</a>
              <span class="ico gray_next"></span>
              <ul class="drawer_list_inner">
                <li>URL 추가</li>
                <li>동영상 추가</li>
                <li>문서 추가</li>
                <li>오디오 추가</li>
                <li>유튜브 추가</li>
              </ul>
            </li>
            <li>
              <a href="#">FAQ</a>
            </li>
          </ul>
        </div>
        
        <div class="exchange_wrap" @click="toggleDrawer()">
          <span class="drawer_atorm_txt">ATORM</span>
          <span class="drawer_atorm_txt2">나가기</span>
          <span class="icon"></span>
        </div>
      </div> 
      <!-- // Drawer -->
      <!-- Drawer Dim -->
      <div id="drawer-overlay" v-if="drawerFlag" @click="toggleDrawer()"></div>
      <!-- // Drawer Dim -->
    </div>
    <!-- //wrap -->

</template>

<script>
import AtormHome from './Atorm_home'
import AtormProductMain from './Atorm_product_main'
import AtormProcessMain from './Atorm_process_main'
import AtormStatusMain from './Atorm_status_main'
export default {
  name: 'Atorm_control',
  components: {'Atorm_home': AtormHome, 'Atorm_product_main': AtormProductMain, 'Atorm_process_main': AtormProcessMain, 'Atorm_status_main': AtormStatusMain},
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      tabIdx: 1,
      component: 'Atorm_home',
      drawerFlag: false,
      title_list_flag: false
    }
  },
  /* vue function */
  methods: {
    onClick (idx) {
      this.tabIdx = idx
      if (idx === 1) {
        this.component = 'Atorm_home'
      } else if (idx === 2) {
        this.component = 'Atorm_product_main'
      } else if (idx === 3) {
        this.component = 'Atorm_process_main'
      } else if (idx === 4) {
        this.component = 'Atorm_status_main'
      }
    },
    toggleDrawer () {
      this.drawerFlag = !this.drawerFlag
    },
    toggleMenu (event) {
      if (event.target.classList.contains('open')) {
        event.target.classList.remove('open')
      } else {
        event.target.classList.add('open')
      }
    }
  }
}
</script>
