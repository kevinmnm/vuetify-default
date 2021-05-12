<template>
  <v-app>
    <v-main>
       <MyComponent />
    </v-main>
  </v-app>
</template>

<script>
import MyComponent from "@/components/MyComponent.vue";
export default {
  name: 'App',
  components: {
     MyComponent,
  },
  data: () => ({
  }),
};
</script>
