<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery study_reflection pd70">
            <!-- header -->
            <div id="header" class="fixed">
                <div class="header_inner line1">
                    <button type="button" class="btn only close"><span class="ico">닫기</span></button>
                    <p class="header_text font_18">리플렉션노트 수정</p>
                    <p class="end">
                        <span class="end_btn2 color_clr2">완료</span>
                    </p>
                </div>
            </div>
            <!-- //header -->            
            <div id="content" class="etc">
                <div class="cell">
                    <div class="inner" style="padding-top:78px;">
                        <ul class="multiList type2">
                            <li>
                                <p class="label-tit14 mb8">제목</p>
                                <slp-text-field placeholder="제목을 입력해주세요" value="제목을 입력해주세요"></slp-text-field>
                            </li>
                            <li>
                                <p class="label-tit14 mb8">내용</p>
                                <slp-text-field placeholder="내용을 입력해주세요." value="본질적인 조건을 생각해보다가 떠오른게 있는데 관련 보고 형식과 리더십의 조건에 대한 강의를 참고하는게 좋겠다. 본질적인 조건을 생각해보다가 떠오른게 있는데 관련 보고 형식과 리더십의 조건에 대한 강의를 참고하는게 좋겠다. "></slp-text-field>
                            </li>
                        </ul>   
                        <p class="label-tit16 mt36 mb10"> 첨부파일 추가</p>
                        <ul v-show="list1.length" class="ulList type4 bot-btn">
                            <li v-for="(item, index) in list1" :key="index">
                            <div>
                                <span class="ico img-a"></span>
                                <span class="at-tit">Solution listup.jpg</span>
                                <div class="fr">
                                <span class="at-num">500KB</span>
                                <span class="ico deletemode_20_black" @click="deleteFileList(index)"></span>
                                </div>
                            </div>                                                             
                            </li>  
                        </ul>
                        <!-- 추가 리스트 --> 
                    </div>
                </div>
            </div>
            <!-- floatingbtn -->
            <div class="fixBtmBtn abs">  
                <a href="#" class="btn sm w100p add" @click="addList1()" ><span class="ico"></span>파일 추가</a>
            </div>
            <!-- //floatingbtn -->                
        </div>
        <!-- //container --> 
    </div>
    <!-- //wrap -->

</template>

<script>
export default {
  name: 'Study_02_reflectionnote_edit_02',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      list1: []
    }
  },
  /* vue function */
  methods: {
    addList1 () {
      this.list1.push('tmp 어학등급 아이템')
    },
    deleteFileList (index) {
      console.log(index, '제거')
      this.list1.splice(index, 1)
    }
  }
}
</script>
