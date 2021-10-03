<script setup lang='ts'>
  import QuizQuestion from '../components/QuizQuestion.vue'
  import SelectDevice from '../components/SelectDevice.vue'
</script>

<template>
  <div class="lg:px-8 h-screen">
    <br/>
    <SelectDevice></SelectDevice>
    <br/>
    <div v-for="question in questions" :key="question">
        <QuizQuestion 
            v-bind:question="question.title"
            v-bind:description="question.desc"></QuizQuestion>
    </div>
  </div>
  
</template>

<style scoped>

</style>

<script lang="ts">

/* sample question data */

var questions = [
    {'title': 'example question', 'desc': 'description 1'},
    {'title': 'another question', 'desc': 'description 2'},
    {'title': 'one more question', 'desc': 'description 3'},
]

</script>
