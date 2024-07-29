<template>
  <div>
    <a >
     Home    </a>
  </div>
  <HelloWorld msg="Media-Visibility" />
</template>

<script>
import HelloWorld from '../components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
  }
};
</script>
