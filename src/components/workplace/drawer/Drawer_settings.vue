<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
        <!-- container -->
        <div id="container" class="mediaquery drawer">
            
            <!-- header -->
            <div id="header" class="fixed">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <p class="header_text font_18">설정</p>
            </div>
            <!-- //header -->

            <div id="content" class="etc">
                <div class="cell">
                    <div class="inner nopad">                     
                    <!-- list -->
                    <ul class="multiList type1">                   
                        <li class="noline" style="padding-top:0">
                            <p class="label-tit14 dpb" style="padding-bottom:10px">권한 변경</p>
                            <label class="labelRdo">
                                <input type="radio" class="rdo" name="test-rdo" checked>
                                <span class="ico">
                                    <span class="innerCircle"></span>
                                </span>
                                <span class="label">User</span>                    
                            </label>
                            <label class="labelRdo">
                                <input type="radio" class="rdo" name="test-rdo">
                                <span class="ico">
                                    <span class="innerCircle"></span>
                                </span>
                                <span class="label">Designer</span>                    
                            </label>                            
                        </li>
                        <li class="noline" style="padding-bottom:0">
                            <strong class="label-tit14">다국어 설정</strong>
                            <select class="select w100p mt8">
                            <option>선택</option>
                            <option>언어</option>
                            <option>언어</option>
                            </select>
                        </li>
                        <li class="pb20">
                            <strong class="label-tit14" placeholder="선택">타임존</strong>
                            <select class="select w100p mt8">
                            <option>선택</option>
                            <option>선택</option>
                            <option>선택</option>
                            </select>
                        </li>                         
                        <li>
                            <strong class="label-tit14">푸시 알림</strong>
                            <label class="labelBtn fr">
                                <input type="checkbox" name="" class="chk">
                                <div class="chk_box"><span class="ball"></span><ul class="txt"><li class="m1"></li><li class="m2"></li></ul></div>
                            </label> 
                        </li>
                        <li>
                            <strong class="label-tit14">버전 정보</strong><button type="button" class="btn14 color_clr2">최신버전으로 업데이트</button>
                        </li>  
                        <li>                           
                            <a href="#"><strong class="label-tit14">오픈 라이선스</strong><span class="black_next"></span></a>
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
  name: 'Drawer_myinfo',
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
