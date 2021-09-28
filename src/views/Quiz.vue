<script setup lang='ts'>
  import DeviceGrid from '../components/DeviceGrid.vue'
  import QuizQuestion from '../components/QuizQuestion.vue'
  import SelectDevice from '../components/SelectDevice.vue'
</script>

<template>
  <div class="lg:px-8 h-screen">
    <br/>
    <SelectDevice></SelectDevice>
    <br/>
    <QuizQuestion 
        question="Example Question"
        description="This would be example question one"></QuizQuestion>
    <QuizQuestion 
        question="Test Question 2"
        description="This would be example question tw0"></QuizQuestion>
    <QuizQuestion 
        question="Another Question"
        description="This would be example question three"></QuizQuestion>
    <QuizQuestion 
        question="One Final Question"
        description="This would be example question four"></QuizQuestion>
  </div>
</template>

<style>
</style>