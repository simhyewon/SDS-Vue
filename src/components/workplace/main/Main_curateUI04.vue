<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery MainType">

        <!-- header 1단형 아이콘 -->
        <div id="header" class="mainType">
            <div class="header_inner line1">
                <button type="button" class="btn allMenu"><span class="ico">전체메뉴</span><span class="ico new"></span></button>
                <ul class="gnbMenu">
                    <!-- selected class:on -->
                    <li class="menu menu_home" :class="{'on': tabIdx == 1}" @click="onClick(1)">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">추천</a>
                    </li>
                    <li class="menu menu_exploration" :class="{'on': tabIdx == 2}" @click="onClick(2)">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">탐색</a>
                    </li>
                    <li class="menu menu_subscription" :class="{'on': tabIdx == 3}" @click="onClick(3)">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">구독</a>
                    </li>
                    <li class="menu menu_learn" :class="{'on': tabIdx == 4}" @click="onClick(4)" style="display:none;">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">학습</a>
                    </li>                
                </ul>
                <p class="main_tit_txt">타이틀</p>
                <button type="button" class="btn btnSch"><span class="ico">검색</span></button>
            </div>
            <div class="header_inner line2">
                <ul class="gnbMenu">
                    <!-- selected class:on -->
                    <li class="menu menu_home on">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">추천</a>
                    </li>
                    <li class="menu menu_exploration">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">탐색</a>
                    </li>
                    <li class="menu menu_subscription">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">구독</a>
                    </li>
                    <li class="menu menu_learn">
                        <a href="#" class="menu_icon"><span class="ico"></span></a>
                        <a href="#" class="menu_txt">학습</a>
                    </li>
                </ul>
            </div>
        </div>
        <!-- //header -->

        <div id="content" class="list">

          <!-- component -->
          <div class="cell">
            <div class="inner">
                <h1 class="h-tit1 fwb700">추천</h1>
                <h2 class="h-tit2 fwb600">정해민님을 위한 맞춤 추천과정</h2>
                <div class="scroll-x type2">
                    <!-- list -->
                    <ul class="ulList type1 mb14">
                        <li>
                            <div class="in-chk">
                            <label class="labelChk2"><input id="" type="checkbox" class="chk" name="" checked="checked"><span class="label">키워드1</span></label>
                            <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">키워드2</span></label>
                            <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">키워드2</span></label>
                            <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">키워드2</span></label>
                            <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">키워드2</span></label>
                            </div>
                        </li>
                    </ul>
                    <!-- //list -->

                    <!-- list -->
                    <ul class="thumList type3">
                        <li>
                            <div class="in">
                            <a href="#">
                                <strong class="tit">꼭 알아야할 실전 비즈니스매너 </strong>
                                <ul class="info">
                                <li>이러닝</li>
                                <li><span class="star ico"></span>4.5</li>
                                </ul>
                                <div class="tagWrap"><span>교재</span><span>환급</span><span>이벤트</span><span>모바일 병행</span></div>
                            </a>
                            </div>
                            <div class="thum">
                                <span class="label">정규</span>
                                <div class="cDim"></div>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_L.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="in">
                            <a href="#">
                                <strong class="tit">꼭 알아야할 실전 비즈니스매너 </strong>
                                <ul class="info">
                                <li>이러닝</li>
                                <li><span class="star ico"></span>4.5</li>
                                </ul>
                                <div class="tagWrap"><span>교재</span><span>환급</span><span>이벤트</span><span>모바일 병행</span></div>
                            </a>
                            </div>
                            <div class="thum">
                                <span class="label">정규</span>
                                <div class="cDim"></div>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_L.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                        </li>
                    </ul>
                    <!-- //list -->
                </div>
                <h2 class="h-tit2 fwb600 mt40">'마케팅직무'를 위한 추천과정</h2>
                <!-- list -->
                <ul class="thumList">
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <span class="label">정규</span>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 자바 스크립트 입문 과정</a>
                            <ul class="info">
                                <li class="color_clr3 fwb">이러닝</li>
                                <li><span class="star ico"></span>4.5</li>
                            </ul>
                            <div class="tagWrap"><span>교재</span><span>모바일병행</span></div>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <span class="label">정규</span>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                                <div class="tagWrap"></div>
                            </a>

                            <a href="#" class="tit">기초부터 예제까지 iOS 개발자를 위한 업무에 바로 쓰는 스플...</a>
                            <ul class="info">
                                <li class="color_clr3 fwb">이러닝</li>
                                <li><span class="star ico"></span>4.5</li>
                            </ul>
                            <div class="tagWrap"></div>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <span class="label">정규</span>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </a>

                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 자바 스크립트 입문 과정</a>
                            <ul class="info">
                                <li class="color_clr3 fwb">이러닝</li>
                                <li><span class="star ico"></span>4.5</li>
                            </ul>
                            <div class="tagWrap"><span>교재</span><span>모바일병행</span></div>
                        </div>
                    </li>
                </ul>
                <!-- //list -->
            </div>
          </div>

                

        </div>
        <div class="btn-quickWrite"></div>
      </div>
      <!-- //container -->     
    </div>
    <!-- //wrap -->
</template>

<script>
export default {
  name: 'Main_curateUI04',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      tabIdx: 1
    }
  },
  /* vue function */
  methods: {
  }
}
</script>
