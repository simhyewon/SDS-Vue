<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery MySpace">

        <!-- header -->
        <div id="header" class="fixed tab">
            <div class="header_inner line1">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <p class="header_text font_18">나의 공간</p>
            </div>
            <div class="header_inner line2 tabMenu scroll-x">
                <ul class="scrollTab">
                    <li><a href="#tab1">정규 학습</a></li><!-- selected class "on" -->
                    <li><a href="#tab2">자율 학습</a></li>
                    <li><a href="#tab3">학습 계획</a></li>
                    <li><a href="#tab4">다운로드</a></li>
                    <li><a href="#tab5">나의 지식 CLIPing</a></li>
                    <li class="on"><a href="#tab6">학습 관리</a></li>
                    <li><a href="#tab7">학습 통계</a></li>
                    <li><a href="#tab8">학점 현황</a></li>
                    <li><a href="#tab9">포인트 현황</a></li>
                    <li><a href="#tab10">쿠폰 관리</a></li>
                </ul>
            </div>
            <div class="blur_wrap">
                <div class="left blur"></div>
                <div class="right blur"></div>
            </div>
        </div>
        <!-- //header -->

        <div id="content" class="list">

          <div class="cell">
            <div class="filterArea ml-18 mr-18">
                <p class="font_15 mono_80 fwb">
                    학습노트 <span class="mono_50">6</span> <span class="ico down"></span>
                    <span class="ico addfolder"></span>
                    <span class="ico filter"></span>
                </p>
            </div>
          </div>

          <div class="cell">
            <div class="inner">
                <!-- list -->
                <ul class="multiList type2 pb15">
                    <li>
                        <div class="txt_wrap">
                            <p class="title">리더십의 본질적인 조건을 생각해보다가...</p>
                            <ul class="info">
                                <li class="mono_65">공개</li>
                                <li class="mono_65">2018.10.10</li>
                                <li class="mono_65"><span class="ico folder_16"></span>기본노트</li>
                            </ul>
                            <ul class="info">
                                <li class="">업무에 바로 쓰는 자바 프로그래밍 입문</li>
                                <li class="">12차시</li>
                            </ul>
                            <span class="chip color2">01:36 <span class="ico play_16 blue"></span></span>
                        </div>
                        <span class="moredot" @click="changeLang1()"></span>
                        <div class="dropdown_wrap" v-show="langFlag1" >
                            <div class="sheetDim" @click="changeLang1()"></div>
                            <div class="dropdown">            
                                <ul  @click="changeLang1()">
                                <!-- 
                                    position 이 변경되어야 한다면 option 처리 로 top , left or right 값 필요 혹은, css로 특정 페이지에서 직접 css로 입력             
                                -->
                                <li>나의 지식 CLIPing</li>
                                <li>나의 지식 CLIPing</li>
                                <li>내가 본 콘텐츠</li>
                                <li>관심 CLIPing</li>
                                <li>나의 지식 CLIPing 활동 이력</li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="txt_wrap">
                            <p class="title">핵심 문구 기억하기</p>
                            <ul class="info">
                                <li class="mono_65">비공개</li>
                                <li class="mono_65">2018.10.10</li>
                                <li class="mono_65"><span class="ico folder_16"></span>비공개노트</li>
                            </ul>
                            <ul class="info">
                                <li class="">업무에 바로 쓰는 자바 프로그래밍 입문</li>
                                <li class="">12차시</li>
                            </ul>
                        </div>
                        <span class="moredot" @click="changeLang2()"></span>
                        <div class="dropdown_wrap" v-show="langFlag2" >
                            <div class="sheetDim" @click="changeLang2()"></div>
                            <div class="dropdown">            
                                <ul  @click="changeLang2()">
                                <!-- 
                                    position 이 변경되어야 한다면 option 처리 로 top , left or right 값 필요 혹은, css로 특정 페이지에서 직접 css로 입력             
                                -->
                                <li>나의 지식 CLIPing</li>
                                <li>나의 지식 CLIPing</li>
                                <li>내가 본 콘텐츠</li>
                                <li>관심 CLIPing</li>
                                <li>나의 지식 CLIPing 활동 이력</li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="txt_wrap">
                            <p class="title">기말고사 범위 예상되는 부분</p>
                            <ul class="info">
                                <li class="mono_65">스크랩</li>
                                <li class="mono_65">홍길동</li>
                                <li class="mono_65">2018.10.10</li>
                                <li class="mono_65"><span class="ico folder_16"></span>스크랩한노트</li>
                            </ul>
                            <ul class="info">
                                <li class="">업무에 바로 쓰는 자바 프로그래밍 입문</li>
                                <li class="">12차시</li>
                            </ul>
                            <span class="chip color2">01:36 <span class="ico play_16 blue"></span></span>
                        </div>
                        <span class="moredot" @click="changeLang3()"></span>
                        <div class="dropdown_wrap" v-show="langFlag3" >
                            <div class="sheetDim" @click="changeLang3()"></div>
                            <div class="dropdown">            
                                <ul  @click="changeLang3()">
                                <!-- 
                                    position 이 변경되어야 한다면 option 처리 로 top , left or right 값 필요 혹은, css로 특정 페이지에서 직접 css로 입력             
                                -->
                                <li>나의 지식 CLIPing</li>
                                <li>나의 지식 CLIPing</li>
                                <li>내가 본 콘텐츠</li>
                                <li>관심 CLIPing</li>
                                <li>나의 지식 CLIPing 활동 이력</li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="txt_wrap">
                            <p class="title">남다른 인생을 사는법</p>
                            <ul class="info">
                                <li class="mono_65">공개</li>
                                <li class="mono_65">2018.10.10</li>
                                <li class="mono_65"><span class="ico folder_16"></span>기본노트</li>
                            </ul>
                            <ul class="info">
                                <li class="">업무에 바로 쓰는 자바 프로그래밍 입문</li>
                                <li class="">12차시</li>
                            </ul>
                            <span class="chip color2">01:20 <span class="ico play_16 blue"></span></span>
                        </div>
                        <span class="moredot" @click="changeLang4()"></span>
                        <div class="dropdown_wrap" v-show="langFlag4" >
                            <div class="sheetDim" @click="changeLang4()"></div>
                            <div class="dropdown">            
                                <ul  @click="changeLang4()">
                                <!-- 
                                    position 이 변경되어야 한다면 option 처리 로 top , left or right 값 필요 혹은, css로 특정 페이지에서 직접 css로 입력             
                                -->
                                <li>나의 지식 CLIPing</li>
                                <li>나의 지식 CLIPing</li>
                                <li>내가 본 콘텐츠</li>
                                <li>관심 CLIPing</li>
                                <li>나의 지식 CLIPing 활동 이력</li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="txt_wrap">
                            <p class="title">제목 없음</p>
                            <ul class="info">
                                <li class="mono_65">공개</li>
                                <li class="mono_65">2018.10.10</li>
                                <li class="mono_65"><span class="ico folder_16"></span>기본노트</li>
                            </ul>
                            <ul class="info">
                                <li class="">업무에 바로 쓰는 자바 프로그래밍 입문</li>
                                <li class="">12차시</li>
                            </ul>
                        </div>
                        <span class="moredot" @click="changeLang5()"></span>
                        <div class="dropdown_wrap" v-show="langFlag5" >
                            <div class="sheetDim" @click="changeLang5()"></div>
                            <div class="dropdown">            
                                <ul  @click="changeLang5()">
                                <!-- 
                                    position 이 변경되어야 한다면 option 처리 로 top , left or right 값 필요 혹은, css로 특정 페이지에서 직접 css로 입력             
                                -->
                                <li>나의 지식 CLIPing</li>
                                <li>나의 지식 CLIPing</li>
                                <li>내가 본 콘텐츠</li>
                                <li>관심 CLIPing</li>
                                <li>나의 지식 CLIPing 활동 이력</li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="txt_wrap">
                            <p class="title">리더십의 본질적인 조건을 생각해보다가...</p>
                            <ul class="info">
                                <li class="mono_65">공개</li>
                                <li class="mono_65">2018.10.10</li>
                                <li class="mono_65"><span class="ico folder_16"></span>기본노트</li>
                            </ul>
                            <ul class="info">
                                <li class="">업무에 바로 쓰는 자바 프로그래밍 입문</li>
                                <li class="">12차시</li>
                            </ul>
                            <span class="chip color2">01:36 <span class="ico play_16 blue"></span></span>
                        </div>
                        <span class="moredot" @click="changeLang6()"></span>
                        <div class="dropdown_wrap" v-show="langFlag6" >
                            <div class="sheetDim" @click="changeLang6()"></div>
                            <div class="dropdown">            
                                <ul  @click="changeLang6()">
                                <!-- 
                                    position 이 변경되어야 한다면 option 처리 로 top , left or right 값 필요 혹은, css로 특정 페이지에서 직접 css로 입력             
                                -->
                                <li>나의 지식 CLIPing</li>
                                <li>나의 지식 CLIPing</li>
                                <li>내가 본 콘텐츠</li>
                                <li>관심 CLIPing</li>
                                <li>나의 지식 CLIPing 활동 이력</li>
                                </ul>
                            </div>
                        </div>
                    </li>
                </ul>
                <!-- //list -->
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
  name: 'MySpace_studymanagement_note',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      langFlag1: false,
      langFlag2: false,
      langFlag3: false,
      langFlag4: false,
      langFlag5: false,
      langFlag6: false
    }
  },
  /* vue function */
  methods: {
    changeLang1 () {
      this.langFlag1 = !this.langFlag1
    },
    changeLang2 () {
      this.langFlag2 = !this.langFlag2
    },
    changeLang3 () {
      this.langFlag3 = !this.langFlag3
    },
    changeLang4 () {
      this.langFlag4 = !this.langFlag4
    },
    changeLang5 () {
      this.langFlag5 = !this.langFlag5
    },
    changeLang6 () {
      this.langFlag6 = !this.langFlag6
    }
  }
}
</script>
