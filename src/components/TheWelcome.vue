<script setup lang="ts">
  import WelcomeItem from './WelcomeItem.vue'
</script>

<template>

  <WelcomeItem>
    <template #icon>
      <img alt="Man" class="logo" src="@/assets/img/man.png" width="50" height="50" />
    </template>
    <template #heading>People</template>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam totam labore delectus pariatur animi, similique quibusdam laudantium harum sit hic quod ut, dolorum nobis ad est repudiandae.</p>
  </WelcomeItem>

</template>
