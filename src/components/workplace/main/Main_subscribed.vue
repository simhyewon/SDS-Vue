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
            
          <!-- //component -->
          <div class="cell">
            <div class="inner">
                <h1 class="h-tit1 fwb700 mb20">구독</h1>
                <h2 class="h-tit2 fwb600 mb10">Channel
                    <div class="fr color_clr2 font_14 fwl">전체보기</div>
                </h2>
                <!-- cBox -->
                <div class="cBox">
                    <!-- tab -->
                    <div class="tabWrap type2">
                        <div  class="tabMenu">
                        <ul>
                            <li class="on"><a href="#tab1">Subscribed</a></li><!-- selected class "on" -->
                            <li><a href="#tab2">New</a></li>
                            <li><a href="#tab3">Popular</a></li>
                            <li><a href="#tab4">Expired</a></li>
                        </ul>
                        </div>

                        <div class="tabCnt dpb" id="tab1"><!-- class "dpb"으로 컨텐츠 영역 노출 / 비노출 제어 -->
                        <div class="scroll-x mr-18">
                            <!-- list -->
                            <ul class="thumList type7">
                                <li>
                                    <div class="in">
                                        <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 자바 스크립트 입문 과정</a>
                                        <a href="#" class="writer">홍길동</a>
                                        <ul class="info">
                                            <li>게시물 10</li>
                                            <li>구독 550</li>
                                            <li><span class="line">P</span> 5</li>
                                        </ul>
                                    </div>
                                    <div class="thum">
                                        <div class="cDim04"></div>
                                        <div class="cDim03"></div>
                                        <div class="thumbnail">
                                            <img src="@/assets/img/thum_no_L2.jpg" class="thumImg" alt="">
                                        </div>
                                    </div>
                                </li>
                                <li>
                                    <div class="in">
                                        <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 자바 스크립트 입문 과정</a>
                                        <a href="#" class="writer">홍길동</a>
                                        <ul class="info">
                                            <li>게시물 10</li>
                                            <li>구독 550</li>
                                            <li><span class="line">P</span> 5</li>
                                        </ul>
                                    </div>
                                    <div class="thum">
                                        <div class="cDim04"></div>
                                        <div class="cDim03"></div>
                                        <div class="thumbnail">
                                            <img src="@/assets/img/thum_no_L2.jpg" class="thumImg" alt="">
                                        </div>
                                    </div>
                                </li>
                                <li>
                                    <div class="in">
                                        <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 자바 스크립트 입문 과정</a>
                                        <a href="#" class="writer">홍길동</a>
                                        <ul class="info">
                                            <li>게시물 10</li>
                                            <li>구독 550</li>
                                            <li><span class="line">P</span> 5</li>
                                        </ul>
                                    </div>
                                    <div class="thum">
                                        <div class="cDim04"></div>
                                        <div class="cDim03"></div>
                                        <div class="thumbnail">
                                            <img src="@/assets/img/thum_no_L2.jpg" class="thumImg" alt="">
                                        </div>
                                    </div>
                                </li>
                            </ul>
                            <!-- //list -->
                        </div>
                        </div>
                    </div>
                    <!-- //tab -->
                </div>
                <!-- //cBox -->
            </div>
          </div>


          <div class="cell">
            <div class="inner">
                <h2 class="h-tit2 fwb600 mb0">Channel Keywords</h2>
                <p class="sub-tit mb10">키워드로 살펴보는 다양한 전문가 채널의 글들</p>
                <!-- list -->
                <ul class="ulList type1">
                    <li>
                        <div class="in-chk">
                        <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">#문화유산 답사 <span class="ico arrow"></span></span></label>
                        <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">#남북정상회담 <span class="ico arrow"></span></span></label>
                        <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">#Peace <span class="ico arrow"></span></span></label>
                        <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">#2018 Design Trend <span class="ico arrow"></span></span></label>
                        <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">#Interaction <span class="ico arrow"></span></span></label>
                        <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">#Big Data <span class="ico arrow"></span></span></label>
                        <label class="labelChk2"><input id="" type="checkbox" class="chk" name=""><span class="label">#Technology <span class="ico arrow"></span></span></label>
                        </div>
                    </li>
                </ul>
                <!-- //list -->
            </div>
          </div>


          <div class="cell">
            <div class="inner">
                <h2 class="h-tit2 fwb600 mb0">Recommended Articles</h2>
                <p class="sub-tit mb10">꼭 한번 읽어보면 좋을 멋진 글</p>
                
                <div class="scroll-x type2">
                    <!-- list -->
                    <ul class="thumList type2">
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_m.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit">만화로 배우는 알기 쉬운 경영전략</a>
                            <a href="#" class="writer">홍길동</a>
                            <ul class="info">
                                <li class="icon">
                                    <span class="view ico"></span><span class="info_value">2,190</span>
                                </li>
                                <li class="icon">
                                    <span class="like ico"></span><span class="info_value">36</span>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_m.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit">만화로 배우는 알기 쉬운 경영전략</a>
                            <a href="#" class="writer">홍길동</a>
                            <ul class="info">
                                <li class="icon">
                                    <span class="view ico"></span><span class="info_value">2,190</span>
                                </li>
                                <li class="icon">
                                    <span class="like ico"></span><span class="info_value">36</span>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_m.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit">만화로 배우는 알기 쉬운 경영전략</a>
                            <a href="#" class="writer">홍길동</a>
                            <ul class="info">
                                <li class="icon">
                                    <span class="view ico"></span><span class="info_value">2,190</span>
                                </li>
                                <li class="icon">
                                    <span class="like ico"></span><span class="info_value">36</span>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_m.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit">만화로 배우는 알기 쉬운 경영전략</a>
                            <a href="#" class="writer">홍길동</a>
                            <ul class="info">
                                <li class="icon">
                                    <span class="view ico"></span><span class="info_value">2,190</span>
                                </li>
                                <li class="icon">
                                    <span class="like ico"></span><span class="info_value">36</span>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_m.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit">만화로 배우는 알기 쉬운 경영전략</a>
                            <a href="#" class="writer">홍길동</a>
                            <ul class="info">
                                <li class="icon">
                                    <span class="view ico"></span><span class="info_value">2,190</span>
                                </li>
                                <li class="icon">
                                    <span class="like ico"></span><span class="info_value">36</span>
                                </li>
                            </ul>
                        </div>
                    </li>
                    </ul>
                    <!-- //list -->
                </div>
            </div>
          </div>

          
          <div class="cell">
            <div class="inner">
                <h2 class="h-tit2 fwb600 mb0">Hey, Day Writer</h2>
                <p class="sub-tit mb10">Hey, Day 지식 창고 작가들</p>
                
                <div class="scroll-x type2">
                    <!-- list -->
                    <ul class="thumList type8">
                        <li>
                            <div class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                            <a href="#" class="tit">홍길동</a>
                            <a href="#" class="sub-tit">멀티캠퍼스 멀티미디어팀</a>
                        </li>
                        <li>
                            <div class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                            <a href="#" class="tit">홍길동</a>
                            <a href="#" class="sub-tit">멀티캠퍼스 멀티미디어팀</a>
                        </li>
                        <li>
                            <div class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                            <a href="#" class="tit">홍길동</a>
                            <a href="#" class="sub-tit">멀티캠퍼스 멀티미디어팀</a>
                        </li>
                        <li>
                            <div class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                            <a href="#" class="tit">홍길동</a>
                            <a href="#" class="sub-tit">멀티캠퍼스 멀티미디어팀</a>
                        </li>
                        <li>
                            <div class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                            <a href="#" class="tit">홍길동</a>
                            <a href="#" class="sub-tit">멀티캠퍼스 멀티미디어팀</a>
                        </li>
                        <li>
                            <div class="thum">
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </div>
                            <a href="#" class="tit">홍길동</a>
                            <a href="#" class="sub-tit">멀티캠퍼스 멀티미디어팀</a>
                        </li>
                    </ul>
                </div>
            </div>
          </div>
          <!-- //component -->

        </div>
        <div class="btn-quickWrite"></div>
      </div>
      <!-- //container -->     
    </div>
    <!-- //wrap -->
</template>

<script>
export default {
  name: 'Main_subscribed',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      tabIdx: 3
    }
  },
  /* vue function */
  methods: {
  }
}
</script>
