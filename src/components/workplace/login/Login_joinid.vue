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
                        <h2 class="tit">통합 아이디 생성</h2>
                        <div class="num">
                            <strong class="color_clr2">3</strong>/<span>6</span>
                        </div>
                    </div>
                        <div class="progBox">
                        <div class="bar clr2" style="width:50%"></div>
                    </div>
                    <!-- B2C -->
                    <p class="txt-desc" style="display:none1;">아래 검색된 아이디 중에서 통합 아이디로 사용하실 아이디를 선택 혹은 입력해주시기 바랍니다.</p>
                    <!-- B2B -->
                    <p class="txt-desc" style="display:none;">아래 검색된 아이디 중에서 통합 아이디로 사용하실 아이디를 선택 혹은 입력해주시기 바랍니다.</p>
                </div>

                <!-- B2B 통합회원가입-->
                <ul class="ulList type2" style="display:none1;">
                  <li>
                    <strong class="label-tit">멀티캠퍼스 이러닝/집합</strong>
                    <ul class="ul-block">
                      <li>
                        <label class="labelRdo">
                          <input type="radio" class="rdo" name="test-rdo">
                          <span class="ico">
                              <span class="innerCircle"></span>
                          </span>
                          <span class="label">CRD_abc1234</span>
                        </label>
                      </li>
                      <li>
                        <label class="labelRdo">
                          <input type="radio" class="rdo" name="test-rdo">
                          <span class="ico">
                              <span class="innerCircle"></span>
                          </span>
                          <span class="label">QMultisos1</span>
                        </label>
                      </li>
                      <li>
                        <label class="labelRdo">
                          <input type="radio" class="rdo" name="test-rdo">
                          <span class="ico">
                              <span class="innerCircle"></span>
                          </span>
                          <span class="label">Multisos1</span>
                        </label>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <strong class="label-tit">OPIc</strong>
                    <ul class="ul-block">
                      <li>
                        <label class="labelRdo">
                          <input type="radio" disabled class="rdo" name="test-rdo">
                          <span class="ico">
                              <span class="innerCircle"></span>
                          </span>
                          <span class="label">미가입</span>
                        </label>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <strong class="label-tit">SERI Pro</strong>
                    <ul class="ul-block">
                      <li>
                        <label class="labelRdo">
                          <input type="radio" class="rdo" name="test-rdo">
                          <span class="ico">
                              <span class="innerCircle"></span>
                          </span>
                          <span class="label">Defg90</span>
                        </label>
                      </li>
                      <li>
                        <label class="labelRdo">
                          <input type="radio" class="rdo" name="test-rdo">
                          <span class="ico">
                              <span class="innerCircle"></span>
                          </span>
                          <span class="label">Defg9Defg90</span>
                        </label>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <strong class="label-tit">직접 입력</strong>
                    <div class="rdoInfoChK">
                      <label class="labelRdo">
                        <input type="radio" class="rdo" name="test-rdo">
                        <span class="ico">
                            <span class="innerCircle"></span>
                        </span>
                      </label>
                      <div class="infoChk2">
                        <slp-text-field placeholder="6~16자의 영 소문자 및 숫자" classObject="underline" ></slp-text-field>
                        <button type="button" class="btn xxs">중복확인</button>
                      </div>
                      <!-- 아이디 체크시 결과 텍스트 -->
                      <p class="InfoChK-resultTxt succ">사용 가능한 아이디입니다.</p>
                      <p class="InfoChK-resultTxt err" style="display:2e;">이미 사용중인 아이디입니다.</p>
                      <!-- //아이디 체크시 결과 텍스트 -->
                    </div>
                  </li>
                </ul>

            </div>
          </div>
        </div>
        <!-- floating button -->
        <div class="fixBtmBtn">
            <ul>
                <li><button type="button" class="btn md">이전</button></li>
                <li><button type="button" class="btn md clr1">다음</button></li>
            </ul>
        </div>
        <!-- //floating button -->
      </div>
      <!-- //container -->     
    </div>
    <!-- //wrap -->

</template>

<script>
export default {
  name: 'Login_joinid',
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
