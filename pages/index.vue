<template>
  <div>
    <Tutorial />
    <div class="temp">Lorem1</div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  data() {
    return {
      temp: 'test',
      temp2: '231'
    }
  },
  methods: {
    tempe() {
      console.log(1)
    }
  }
})
</script>
