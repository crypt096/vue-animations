<template>
  <div class="about">
    <transition 
    appear
    @before-enter="beforeEnter"
    @enter="enter"
    >
      <h1>About</h1>
    </transition>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum aperiam officia possimus delectus inventore quod quisquam culpa voluptas iusto, quae maiores quo dolorum, corporis laboriosam a dolore consequatur assumenda nam!</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum aperiam officia possimus delectus inventore quod quisquam culpa voluptas iusto, quae maiores quo dolorum, corporis laboriosam a dolore consequatur assumenda nam!</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum aperiam officia possimus delectus inventore quod quisquam culpa voluptas iusto, quae maiores quo dolorum, corporis laboriosam a dolore consequatur assumenda nam!</p>
  </div>
</template>

<script>
import { ref } from 'vue';

export default {
  setup() {

    const beforeEnter = (el) => {
      
    }

    const enter = (el) => {

    }

    return { beforeEnter, enter }
  }
}
</script>

<style>
  .about {
    max-width: 600px;
    margin: 20px auto;
  }
</style>