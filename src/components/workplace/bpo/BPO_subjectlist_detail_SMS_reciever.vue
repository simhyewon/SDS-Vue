<template>
 <!-- eslint-disable -->
    <!-- wrap -->
    <div id="wrap" class="colorCode2">        
        <!-- container -->
        <div id="container" class="mediaquery drawer bpo sms">
            
            <!-- header -->
            <div id="header" class="fixed">
                <button type="button" class="btn only prev"><span class="ico">이전</span></button>
                <p class="header_text font_18">SMS 보내기</p><button type="button" class="btn14 color_clr2">발송</button>
            </div>
            <!-- //header -->
       
        <div id="content" class="etc">
          <div class="cell">
            <div class="inner">

                <div class="tabCnt dpb pt0"><!-- class "dpb"으로 컨텐츠 영역 노출 / 비노출 제어 -->
                                                        
                        <p class="title_line">
                            <span class="title_txt">발송대상</span><span class="total_txt">총</span><strong class="fwb600 count">53</strong>명
                            <span class="fr ico accordion_up"></span>
                        </p>
                        <!-- list -->                 
                        <ul class="multiList type1">                         
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">모두</span>
                            </li>
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>                                
                            </li>
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li> 
                             <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li>
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li> 
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li> 
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li>  
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li>
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li>
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li>
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li>
                            <li>
                                <slp-checkbox value="true" class="mr10"></slp-checkbox>
                                <span class="label-tit">홍길동</span>
                            </li>                                                           
                        </ul>
                                    
                        <!-- //list -->
                </div>   

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
