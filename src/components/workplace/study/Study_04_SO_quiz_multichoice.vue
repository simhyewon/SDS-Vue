<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
        <div id="container" class="mediaquery study_quiz_ox pd70">

            <!-- header  + 확장형  헤더  ::: hide_header  클래스는 fixed 붙으면 hidden 처리 -->
            <div v-if="headerType == '1'" id="header" class="expand wh quiz-head-bg">          
                <div class="header_inner line1">
                    <button type="button" class="btn only prev"><span class="ico2 prev-wh"></span></button>
                    <div class="page-btn">
                        <span class="ico back-wh"></span>
                        <div class="num "><span>03</span>/<span>36</span>p</div>
                        <span class="ico next-wh"></span>
                    </div>
                    <p class="header_text  font_19"> 스크롤시  header 에 fixed 클래스 추가</p>
                </div>  
                <div class="hide_header" style="background:rgba(0,0,0,0.45);  padding-top:66px; padding-bottom:26px">                
                    <div class="hide-inner">
                        <span class="chip wh">퀴즈</span>                         
                        <p class="h-tit1">중간퀴즈 : 자바의 특성과 개념에 대해 알아보기</p>
                        <p class="h-tit5">
                            <span>총 6문항</span>
                        </p>
                    </div>
                </div>
            </div>
            <!-- //header -->


            <!-- header + 확장형 + tab  헤더  ::: hide_header  클래스는 fixed 붙으면 hidden 처리 -->
            <div v-if="headerType == '2'" id="header" class="tab">          
                <div class="header_inner line1">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <p class="header_text font_19"> 스크롤시  header 에 fixed 클래스 추가</p>
                </div>  
                <div class="header_inner line2 tabMenu">
                    <ul class="fixTab">
                    <li class="on"><a href="#tab1">동영상재테크</a></li><!-- selected class "on" -->
                    <li><a href="#tab2">이미지투데이</a></li>
                    <li><a href="#tab3">인문학이야기</a></li>
                    <li><a href="#tab3">인문학이야기</a></li>
                    </ul>
                </div>  
                <div class="hide_header" style="background:#e6eaf5; padding-top:56px; padding-bottom:26px">                
                    <div class="head-inner"> 
                        <span class="chip">FAQ</span>     
                        <p class="h-tit1">공지사항 타이틀 영역입니다. 공지사항 타이틀</p>
                        <p class="ico-group">
                            <span class="ico clip"></span>
                            <span>2,190</span>
                            <span class="pipe"></span>
                            <span class="ico view"></span>
                            <span>첨부파일</span>
                        </p>
                    </div>
                </div>
            </div>
            <!-- //header -->

            
            <!-- header scroll 헤더  작업중-->
            <div v-if="headerType == '3'" id="header" class="tab">
                
                <div class="header_inner line1">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <p class="header_text font_19"> 스크롤시  header 에 fixed 클래스 추가</p>
                </div>            
                <div class="header_inner line2 tabMenu scroll-x">
                    <ul class="scrollTab">
                    <li class="on"><a href="#tab1">동영상재테크</a></li><!-- selected class "on" -->
                    <li><a href="#tab2">이미지투데이</a></li>
                    <li><a href="#tab3">인문학이야기</a></li>
                    <li><a href="#tab3">인문학이야기</a></li>
                    <li><a href="#tab3">인문학이야기</a></li>
                    </ul>
                </div>     
                <div class="hide_header" style="background:#e6eaf5; padding-top:56px; padding-bottom:26px">                
                    <div class="head-inner"> 
                        <span class="chip">FAQ</span>     
                        <p class="h-tit1">공지사항 타이틀 영역입니다. 공지사항 타이틀</p>
                        <p class="ico-group">
                            <span class="ico clip"></span>
                            <span>2,190</span>
                            <span class="pipe"></span>
                            <span class="ico view"></span>
                            <span>첨부파일</span>
                        </p>
                    </div>
                </div>
            </div>
            <!-- //header -->        
            <div id="content" class="etc">
                <div class="cell">
                    <div class="inner"> 
                        <p class="inner-txt">학습을 통해 얼마나 배웠는지 QUIZ를 통해 알아볼까요? 퀴즈를 통해서 본인의 학습성과를 테스트하고 그 결과를 확인해 볼 수 있습니다. 퀴즈의 점수는 중간성적에 반영됩니다.</p>
                        <p class="line02"></p>
                        <p class="txt-tit">01. 다음 지문을 읽고 <span class="underline">틀린 것</span>을 고르시오. (5점)</p>
                        <p class="inner-txt op65 mb20">Java 기반의 웹 프레임워크. 로드 존슨이 2002년에 출판한 저서 Expert One-on-One J2EE Design and Development에서 선보인 소스 코드를 시작으로 점점 발전하게 되었다. 2003년 6월에 최초로 공개되었다. </p>
                        <ul class="ul-block com-rdo">
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo" :value="rdos[0]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label"  >① EJB를 주 프레임워크로 사용할 때 불편했을 점을 해소하려고 개발되었다.</span>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo" :value="rdos[1]" >
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >② 2002년 로드존슨이 출판한 도서가 스프링의 시작이라고 보는 견해가 있다.</span>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo" :value="rdos[2]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >③ 2003년 Apache 2.0 License로 최초 공개</span>                    
                                </label>
                            </li>
                            <li>
                                <label  class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo" :value="rdos[3]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >④ 2003년 상용으로 소개되었으나 이후 오픈소스로 바뀌었다.</span>                    
                                </label>
                            </li>
                            <li>
                                <label  class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo" :value="rdos[4]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >⑤ 동적인 웹 사이트를 개발하기 위한 여러 가지 서비스를 제공하고 있다.</span>                    
                                </label>
                            </li>
                        </ul>     
                        <p class="hr"></p>
                        <p class="txt-tit">02. 마이동풍은 이백의 시에서 유래한 말이다. 여기에서 동풍은 어떤 계절의 바람일까?</p>                        
                        <ul class="ul-block com-rdo">
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo2" :value="rdos2[0]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >① 봄</span>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo2" :value="rdos2[1]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label"  >② 여름</span>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo2" :value="rdos2[2]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >③ 가을</span>                    
                                </label>
                            </li>
                            <li>
                                <label  class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo2" :value="rdos2[3]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >④ 겨울</span>                    
                                </label>
                            </li>
                        </ul> 
                        <p class="hr"></p>
                        <p class="txt-tit">03. 다음 중 OO에 해당하는 것을 고르세요.</p>
                        <p class="inner-txt op65 mb20">태양계에는 항성인 태양과 그 가까이로부터 수성, 금성, 지구, 화성, 즉 지구형 행성이 순서대로 나열되어 있으며 그 다음에 유성대(asteroid belt)가 존재한다. </p>
                        <ul class="ul-block com-rdo img-rdo">
                            <li>
                                <label class="labelRdo" @click="activate(1)">
                                    <input type="radio" class="rdo" v-model="rdo3" :value="rdos3[0]">
                                    <span class="ico " style="top:15px;">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <div class="label"   :class="{ border_clr2 : active_el == 1 }" ><span class="ico num-cir">1</span> <img src="@/assets/img/study_quiz_choice.png" class="multi-img" alt=""/> </div>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" @click="activate(2)">
                                    <input type="radio" class="rdo" v-model="rdo3" :value="rdos3[1]">
                                    <span class="ico" style="top:15px;">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <div class="label"   :class="{ border_clr2 : active_el == 2 }" ><span class="ico num-cir">2</span> <img src="@/assets/img/study_quiz_choice.png" class="multi-img" alt=""/> </div>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" @click="activate(3)">
                                    <input type="radio" class="rdo" v-model="rdo3" :value="rdos3[2]">
                                    <span class="ico" style="top:15px;">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <div class="label"   :class="{ border_clr2 : active_el == 3 }" ><span class="ico num-cir">3</span> <img src="@/assets/img/study_quiz_choice.png" class="multi-img" alt=""/> </div>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" @click="activate(4)">
                                    <input type="radio" class="rdo" v-model="rdo3" :value="rdos3[3]">
                                    <span class="ico" style="top:15px;">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <div class="label"   :class="{ border_clr2 : active_el == 4 }" ><span class="ico num-cir">4</span> <img src="@/assets/img/study_quiz_choice.png" class="multi-img" alt=""/> </div>                    
                                </label>
                            </li>
                        </ul>     
                        <p class="hr"></p>

                        <p class="txt-tit">04. 다음 중 OO에 해당하는 것을 고르세요.</p>
                        <p><img class="single-img" src="@/assets/img/study_quiz_choice.png" alt=""></p>
                        <p class="inner-txt op65 mb20">Java 기반의 웹 프레임워크. 로드 존슨이 2002년에 출판한 저서 Expert One-on-One J2EE Design and Development에서 선보인 소스 코드를 시작으로 점점 발전하게 되었다. 2003년 6월에 최초로 공개되었다. </p>
                        <ul class="ul-block com-rdo">
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo4" :value="rdos4[0]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >① EJB를 주 프레임워크로 사용할 때 불편했을 점을 해소하려고 개발되었다.</span>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo4" :value="rdos4[1]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label"  >② 2002년 로드존슨이 출판한 도서가 스프링의 시작이라고 보는 견해가 있다.</span>                    
                                </label>
                            </li>
                            <li>
                                <label class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo4" :value="rdos4[2]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >③ 2003년 Apache 2.0 License로 최초 공개되었다.</span>                    
                                </label>
                            </li>
                            <li>
                                <label  class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo4" :value="rdos4[3]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >④ 2003년 상용으로 소개되었으나 이후 오픈소스로 바뀌었다.</span>                    
                                </label>
                            </li>
                            <li>
                                <label  class="labelRdo" >
                                    <input type="radio" class="rdo" v-model="rdo4" :value="rdos4[4]">
                                    <span class="ico">
                                        <span class="ico chk-blue"></span>
                                    </span>
                                    <span class="label" >⑤ 동적인 웹 사이트를 개발하기 위한 여러 가지 서비스를 제공하고 있다.</span>                    
                                </label>
                            </li>
                        </ul>
                    </div>
                    <!-- //inner -->
                </div>  
            </div>

            <!-- floatingbtn -->
            <div class="fixBtmBtn abs">  
                <button type="button" class="btn md " :class="{ clr1 : rdo && rdo2 && rdo3 && rdo4}">정답확인</button>
            </div>
            <!-- //floatingbtn -->
        </div>
        <!-- //container --> 
    </div>
    <!-- //wrap -->
</template>

<script>
/*
  headerType
  1 : 기본헤더 + 확장 ,  2 : 헤더 + 확장 + 텝  or  헤더 + 텝 ,  3 : 헤더 + 확장 + 스크롤텝
*/
export default {
  name: 'Study_04_SO_quiz_multichoice',
  props: {
  },
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      headerType: 1,
      rdo: undefined,
      rdos: ['one', 'two', 'three', 'four', 'five'],
      rdo2: undefined,
      rdos2: ['one', 'two', 'three', 'four'],
      rdo3: undefined,
      rdos3: ['one', 'two', 'three', 'four'],
      rdo4: undefined,
      rdos4: ['one', 'two', 'three', 'four', 'five']
    }
  },
  /* vue function */
  methods: {
    activate: function (el) {
      this.active_el = el
    }
  }
}
</script>
