<template>
<!--
<div class="full-width full-height row wrap justify-start items-start content-start">
  <div class="col-8 q-ma-sm" style="overflow: auto; min-height: 98%; max-height: 98%; background: gray;">
    .col
  </div>
<div class="column col q-mr-sm" style="overflow: auto; min-height: 99%; max-height: 99%;" >
     <div class="col" style="background: gray;">
        .col
      </div>
      <div class="col" style="background: gray;">
        .col
      </div>
  </div>
      <div class="column col q-mt-sm q-mb-sm q-mr-sm " style="height: 98%;">
      <div class="col col-md-2 col-bg q-mb-sm" >.col</div>
      <div class="col col-md-10 col-bg">.col</div>
    </div>
</div>
-->
<div class="row" style="height: 100%;">
  <div class="col-8 q-mt-sm q-ml-sm q-mb-sm" style="background: gray;">First column</div>
  <div class="column col q-ma-sm" style="height: 98%;">
      <div class="col q-mb-sm" style="background: blue;">
        .col
      </div>
      <div class="col-8" style="background: red;">
        .col-8
      </div>
    </div>
</div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>

<style lang="scss">

</style>
