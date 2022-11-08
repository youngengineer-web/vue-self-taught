<template>
    <h1>It is a test</h1>
    <h4>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Asperiores, dicta!</h4>
    <TestTwo/>
</template>

<script>
import TestTwo from './TestTwo.vue'

export default {
  name: 'TestOne',
  components: {
    TestTwo
  }
}

</script>