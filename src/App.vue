<template>
<div>
<div v-for="item in data" :key="item.id">
  <div>{{item.title}}</div>
  <div>{{item.description}}</div>
</div>
</div>
 
</template>

<script setup>
// import QuestionValue from './question.json'

const data =  [
    {
       "title": "Clean the kitchen",
       "description": "Mop the floor, wipe the countertop and don't forget to take out the trash!"
    },
    {
       "title": "Call Mom",
       "description": "It's her birthday!"
    },
    {
       "title": "Water flowers",
       "description": "They need water, or they will die."
    },
    {
        "title": "Clean the kitchen",
        "description": "Mop the floor, wipe the countertop and don't forget to take out the trash!"
     },
     {
        "title": "Call Mom",
        "description": "It's her birthday!"
     },
     {
        "title": "Water flowers",
        "description": "They need water, or they will die."
     },
     {
        "title": "Clean the kitchen",
        "description": "Mop the floor, wipe the countertop and don't forget to take out the trash!"
     },
     {
        "title": "Call Mom",
        "description": "It's her birthday!"
     },
     {
        "title": "Water flowers",
        "description": "They need water, or they will die."
     }
 ] 
</script>



