<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery searchcompany">
        <!-- header -->
        <div id="header" class="tab">          
          <div class="header_inner line1">
            <button type="button" class="btn only close"><span class="ico">닫기</span></button>
            <p class="header_text font_18">회사검색</p>
          </div>  
          <div class="header_inner line2 tabMenu">
              <ul class="fixTab">
                <li class="on"><a href="#tab1">회사명</a></li><!-- selected class "on" -->
                <li><a href="#tab2">사업자 등록번호</a></li>
              </ul>
          </div>
          <div class="hide_header">
            <div class="hide_inner"><h1 class="h-tit1">회사 검색</h1></div>            
          </div> 
        </div>
        <!-- //header -->
        
        <div id="content" class="etc">
          <div class="cell">
            <div class="inner">
                <!-- 회사명 -->
                <div style="display:block;">
                  <strong class="label-tit">회사명 검색</strong>
                  <div class="intSchBox">
                    <div class="search-wrapper">
                        <input type="text"  pattern="^\s+" class="input" placeholder="회사명 입력" />
                        <button class="close-icon" type="button" style="right:0"></button>
                    </div>
                  </div>
                </div>
                <!-- 회사명 -->

                <!-- 사업자 등록번호 -->
                <div style="display:none;">
                  <strong class="label-tit">사업자 등록번호 검색</strong>
                  <div class="intSchBox">
                    <div class="search-wrapper">
                        <input type="text"  pattern="^\s+" class="input" placeholder="사업자 등록번호 입력" />
                        <button class="close-icon" type="button" style="right:0"></button>
                    </div>
                  </div>
                </div>
                <!-- 사업자 등록번호 -->

            </div>
          </div>
        </div>


      </div>
      <!-- //container --> 
        
      
    </div>
    <!-- //wrap -->

</template>

<script>
export default {
  name: 'Login_searchcompany',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
    }
  },
  /* vue function */
  methods: {
  }
}
</script>
