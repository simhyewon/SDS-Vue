<template>
<!-- eslint-disable -->
<div> 
    <strong class="label-tit-14 fwb" style=" display:inline-block; margin-bottom:8px;">회사명 검색</strong>
     <div class="intSchBox">
        <div class="search-wrapper">
            <input type="text" ref="input01" pattern="^\s+" class="input" placeholder="회사명 입력" />
            <button class="close-icon" type="button" @click="delTxt" style="right:0"></button>
        </div>
    </div>
</div>
</template>

<script>
/* eslint-disable */
export default {
  name: 'Login_searchcompany1',
  method: {
      delTxt () {
        this.$emit('childs-event', 'hello!')
      }
  }
}
</script>
