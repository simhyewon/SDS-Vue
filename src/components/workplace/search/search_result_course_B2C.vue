<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
      <!-- container -->
      <div id="container" class="mediaquery search">

        <!-- header -->
        <div id="header" class="fixed tab">
            <div class="header_inner line1">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <div class="search-wrapper">
                    <input type="text"  pattern="^\s+" class="input noline" placeholder="검색어를 입력해 주세요" value="자바스크립트" />
                    <button class="close-icon" type="button"></button>
                </div>
            </div>
            <div class="header_inner line2 scroll-x">
                <!-- list -->
                <ul class="ulList type1 pl18">
                    <li>
                        <div class="in-chk">
                            <slp-checkbox type="button" value="true">이러닝</slp-checkbox>
                            <slp-checkbox type="button">집합</slp-checkbox>
                            <slp-checkbox type="button">복합</slp-checkbox>
                            <slp-checkbox type="button">지식과정</slp-checkbox>
                            <slp-checkbox type="button">부가서비스</slp-checkbox>
                        </div>
                    </li>
                </ul>
                <!-- //list -->
            </div>
        </div>
        <!-- //header -->
        <div id="content" class="list">
        
          <div class="cell">
            <div class="filterArea ml-18 mr-18">
                <p class="font_15 mono_100 fwb">총 검색결과 <span class="color_clr2">468</span></p>
                <span class="ico filter"></span>
            </div>
          </div>

          <div class="cell">
            <div class="inner">
                <h2 class="h-tit2 fwb600 mb20">
                    일반 <span class="color_clr2">468</span>
                    <div class="fr color_clr2 font_14 fwl">전체보기</div>
                </h2>
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
                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 <strong>자바스크립트</strong> 입문 과정</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                                <li><div class="tagWrap"><span>교재</span><span>이벤트</span></div></li>
                            </ul>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <span class="label">자율</span>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit"><strong>자바스크립트</strong>기초부터 예제까지 iOS 개발자를 위한 업무에 바로 쓰는 스플...</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                            </ul>
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
                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 <strong>자바스크립트</strong> 입문 과정</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                                <li><div class="tagWrap"><span>교재</span><span>이벤트</span></div></li>
                            </ul>
                        </div>
                    </li>
                </ul>
                <!-- //list -->
            </div>
          </div>

        
          <div class="cell">
            <div class="inner">
                <h2 class="h-tit2 fwb600 mb20">
                    독서통신 <span class="color_clr2">156</span>
                    <div class="fr color_clr2 font_14 fwl">전체보기</div>
                </h2>
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
                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 <strong>자바스크립트</strong> 입문 과정</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                                <li><div class="tagWrap"><span>교재</span><span>이벤트</span></div></li>
                            </ul>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <span class="label">자율</span>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit"><strong>자바스크립트</strong>기초부터 예제까지 iOS 개발자를 위한 업무에 바로 쓰는 스플...</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                            </ul>
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
                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 <strong>자바스크립트</strong> 입문 과정</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                                <li><div class="tagWrap"><span>교재</span><span>이벤트</span></div></li>
                            </ul>
                        </div>
                    </li>
                </ul>
                <!-- //list -->
            </div>
          </div>
          
        
          <div class="cell">
            <div class="inner">
                <h2 class="h-tit2 fwb600 mb20">
                    전화외국어 <span class="color_clr2">156</span>
                    <div class="fr color_clr2 font_14 fwl">전체보기</div>
                </h2>
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
                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 <strong>자바스크립트</strong> 입문 과정</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                                <li><div class="tagWrap"><span>교재</span><span>이벤트</span></div></li>
                            </ul>
                        </div>
                    </li>
                    <li>
                        <div class="in">
                            <a href="#" class="thum">
                                <span class="label">자율</span>
                                <div class="thumbnail">
                                    <img src="@/assets/img/thum_no_s.jpg" class="thumImg" alt="">
                                </div>
                            </a>
                            <a href="#" class="tit"><strong>자바스크립트</strong>기초부터 예제까지 iOS 개발자를 위한 업무에 바로 쓰는 스플...</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                            </ul>
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
                            <a href="#" class="tit">초보자를 위한 업무에 바로 쓰는 <strong>자바스크립트</strong> 입문 과정</a>
                            <p class="mono_80 font_13 multiline line1"><a href="#">글로벌 비즈니스</a> > <a href="#">글로벌 비즈니스의</a></p>
                            <ul class="info mt8">
                                <li class="mono_80"><span>1,135,000</span>원</li>
                                <li><div class="tagWrap"><span>교재</span><span>이벤트</span></div></li>
                            </ul>
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
  name: 'search_result_course_B2C',
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
