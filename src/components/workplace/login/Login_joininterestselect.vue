<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery join pd70">
          
            <div id="content" class="etc">
                <div class="cell">
                    <div class="inner">

                        <h1 class="h-tit">회원가입</h1>

                        <div class="stepper">
                            <div class="clearfix">
                                <h2 class="tit">관심사 선택</h2>
                                <div class="num">
                                    <strong class="color_clr2">5</strong>/<span>6</span>
                                </div>
                            </div>
                                <div class="progBox">
                                <div class="bar clr2" style="width:83%"></div>
                            </div>
                            <p class="txt-desc">관심사를 선택하시면 회원님에게 맞는 다양한 학습강의들을 추천해드립니다.</p>
                        </div>


                        <!-- list -->
                        <ul class="ulList type1 mt48">
                            <li>
                                <strong class="label-tit">관심 분야</strong>
                                <div class="in-chk">
                                    <slp-checkbox type="button" @input="pushChk(1)">경영 / 리더십</slp-checkbox>
                                    <slp-checkbox type="button"  @input="pushChk(1)">금융</slp-checkbox>
                                    <slp-checkbox type="button"  @input="pushChk(1)">직무 / 자격</slp-checkbox>
                                    <slp-checkbox type="button" @input="pushChk(1)">OPIC / 외국어</slp-checkbox>
                                    <slp-checkbox type="button" @input="pushChk(1)">인문 / 교양 / 시사</slp-checkbox>
                                </div>
                            </li>
                            <li>
                                <strong class="label-tit">선호 과정</strong>
                                <div class="in-chk">
                                    <slp-checkbox type="button" @input="pushChk(2)">이러닝</slp-checkbox>
                                    <slp-checkbox type="button"  @input="pushChk(2)">집합</slp-checkbox>
                                    <slp-checkbox type="button" @input="pushChk(2)">지식</slp-checkbox>
                                </div>
                            </li>
                            <li>
                                <strong class="label-tit">선호 강의</strong>
                                <div class="in-chk">
                                    <slp-checkbox type="button" @input="pushChk(3)">Instructor-led</slp-checkbox>
                                    <slp-checkbox type="button"  @input="pushChk(3)">Self-paced with labs</slp-checkbox>
                                    <slp-checkbox type="button" @input="pushChk(3)">Self-paced</slp-checkbox>
                                </div>
                            </li>
                        </ul>
                        <!-- //list -->


                    </div>
                </div>
            </div>

            <!-- floating button -->
            <div class="fixBtmBtn">
                <!-- disable 해제시 활성화 -->
                <ul>
                    <li><button type="button" class="btn md">이전</button></li>
                    <li><button type="button" class="btn md" :class="{ clr1 : chk && chk2 && chk3 }">다음</button></li>
                </ul>
            </div>
            <!-- //floating button -->
            
            
        </div>
        <!-- //container -->   

    </div>
    <!-- //wrap -->

</template>

<script>
/* eslint-disable */
export default {
  name: 'Login_joininterest',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      value: true,
      chk: '',
      chk2: '',
      chk3: ''
    }
  },
  /* vue function */
  methods: {  
    pushChk (el) {
      if( el == 1) {
        this.chk = event.target.value
        console.log(event.target.value)
        // if(event.target.value == true ) {
        //     console.log(event.target.value)
        // } else if(event.target.value == false) {
        //     this.chk = ''
        // }        
      } else if ( el == 2) {
        console.log(event.target.value)
        this.chk2 = event.target.value
      } else if ( el == 3) {
        this.chk3 = event.target.value
      } 
    }  
  },
  computed: {
    
  }
}
</script>
