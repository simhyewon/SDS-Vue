<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
        <!-- container -->
        <div id="container" class="mediaquery drawer inquiry">
            
            <!-- header -->
            <div id="header" class="fixed">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <p class="header_text font_18">설문</p>
            </div>
            <!-- //header -->
       
        <div id="content" class="etc">
          <div class="cell">
            <div class="inner">

                <div class="tabCnt dpb pt0" id="tab1"><!-- class "dpb"으로 컨텐츠 영역 노출 / 비노출 제어 -->
                                <!-- list -->                                 
                                        <h1 class="h-tit5 title_line">
                                            <span class="total_txt">총</span>
                                            <strong class="fwb600 count">12</strong><span>건</span>
                                            <a href="#"><span class="ico down fr"></span><span class="total fr">전체</span></a>
                                        </h1>
                
                                        <ul class="multiList type3">
                                            <li>
                                                <div class="in">                                                                                        
                                                    <div class="multiline contents">
                                                    LMS 설문 테스트입니다.LMS 설문 테스트입니다.<br>LMS 설문 테스트입니다.
                                                    </div>                                                     
                                                    <ul class="info">
                                                    <li class="fwb color_clr3">진행중</li>
                                                    <li class="icon"><span class="date">2018.10.10 ~ 2018.10.20</span></li>
                                                    
                                                    <button type="button" class="btn13 color_clr2 fr"> 설문하기</button> 
                                                    </ul>
                                                </div>                                                
                                            </li>
                                             <li>
                                                <div class="in">                                                                                        
                                                    <div class="multiline contents">
                                                    자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.
                                                    </div>                                                     
                                                    <ul class="info">
                                                    <li class="fwb color_clr3">과정문의</li>
                                                    <li class="icon"><span class="date">2018.10.10</span></li>
                                                    <li class="icon reply fr"><span class="check_16_blue ico"></span><span>답변완료</span></li>
                                                    </ul>
                                                </div>                                                
                                            </li>
                                             <li>
                                                <div class="in">                                                                                        
                                                    <div class="multiline contents">
                                                    자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.
                                                    </div>                                                     
                                                    <ul class="info">
                                                    <li class="fwb color_clr3">과정문의</li>
                                                    <li class="icon"><span class="date">2018.10.10</span></li>
                                                    <li class="icon reply fr"><span class="check_16_blue ico"></span><span>답변완료</span></li>
                                                    </ul>
                                                </div>                                                
                                            </li>
                                             <li>
                                                <div class="in">                                                                                        
                                                    <div class="multiline contents">
                                                    자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.
                                                    </div>                                                     
                                                    <ul class="info">
                                                    <li class="fwb color_clr3">과정문의</li>
                                                    <li class="icon"><span class="date">2018.10.10</span></li>
                                                    <li class="icon reply fr"><span class="check_16_blue ico"></span><span>답변완료</span></li>
                                                    </ul>
                                                </div>                                                
                                            </li>
                                             <li>
                                                <div class="in">                                                                                        
                                                    <div class="multiline contents">
                                                    자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.
                                                    </div>                                                     
                                                    <ul class="info">
                                                    <li class="fwb color_clr3">과정문의</li>
                                                    <li class="icon"><span class="date">2018.10.10</span></li>
                                                    <li class="icon reply fr"><span class="check_16_blue ico"></span><span>답변완료</span></li>
                                                    </ul>
                                                </div>                                                
                                            </li>
                                             <li>
                                                <div class="in">                                                                                        
                                                    <div class="multiline contents">
                                                    자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.자료실 타이틀 영역입니다.
                                                    </div>                                                     
                                                    <ul class="info">
                                                    <li class="fwb color_clr3">과정문의</li>
                                                    <li class="icon"><span class="date">2018.10.10</span></li>
                                                    <li class="icon reply fr"><span class="check_16_blue ico"></span><span>답변완료</span></li>
                                                    </ul>
                                                </div>                                                
                                            </li>
                                                              
                                        </ul>
                                    
                                <!-- //list -->
                              </div>   

            </div>
          </div>
        </div>

      </div>
      <!-- //container --> 

        <!-- layer wrap -->
        <slp-popup title="네트워크 확인" confirmInput="확인">
            <div class="ly-body">
                <p>현재 회원님의 모바일이 네트워크에 연결되어 있지 않으므로 서비스를 이용하실 수 없습니다. 네트워크 연결을 확인 한 후 다시 실행 해 주시기 바랍니다.</p>
            </div>
        </slp-popup>
        <!-- //layer wrap -->

    </div>
    <!-- //wrap -->

</template>

<script>
export default {
  name: 'components_tabheader',
  /* vue lifecycle */
  created () {
  },
  mounted () {
  },
  /* vue data */
  data () {
    return {
      headerType: 2
    }
  },
  /* vue function */
  methods: {
  }
}
</script>
