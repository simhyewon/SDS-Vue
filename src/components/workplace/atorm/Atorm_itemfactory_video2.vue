<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
        <!-- container -->
        <div id="container" class="mediaquery atorm atorm_itemfactory">
            
            <!-- header -->
            <div id="header" class="fixed">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <p class="header_text font_18">동영상</p><button type="button" class="btn16 color_clr2">저장</button>
            </div>
            <!-- //header -->

            <div id="content" class="etc">
                <div class="cell">
                    <div class="inner pd22">  
                    <div class="oh">
                        <h2 class="label-tit20 fl"><strong>공개여부</strong></h2>
                                <label class="labelBtn fr">
                                    <input type="checkbox" name="" class="chk">
                                    <div class="chk_box"><span class="ball"></span><ul class="txt"><li class="m1"></li><li class="m2"></li></ul></div>
                                </label>  
                    </div>   
                    <p class="tit_desc">공개하시면  다른 사람이 내 아이템을 활용하여 과정을 만들 수 있습니다.</p> 

                    <p class="hr" style="margin:26px -24px 18px"></p>                     
                    <!-- list -->
                    <ul class="multiList type3"> 
                        <li style="padding-top:0">
                            <strong class="label-tit14 tit_essential">아이템 명</strong>
                            <slp-text-field placeholder="아이템 명을 입력해 주세요." class="mt6"></slp-text-field>
                        </li>
                        <li style="padding:15px 0">                            
                            <strong class="label-tit14 tit_essential">동영상 업로드</strong>
                            <p class="file_name">multismart2018.mp4</p>
                            <a href="#"><span class="ico deletemode_20 fr"></span></a>
                        </li>
                        <li>
                            <strong class="label-tit14 tit_essential">스크립트</strong>
                            <slp-text-field placeholder="스크립트를 입력하세요" class="mt6"></slp-text-field>
                            <span class="text_limit">0/300</span>
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
