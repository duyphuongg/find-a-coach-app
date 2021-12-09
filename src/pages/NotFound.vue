<template>
  <div>
    <RatingStar v-bind="config"/>
  </div>
</template>

<script>
import RatingStar from './../components/RatingStar.vue';
export default {
  components: {
    RatingStar,
  },
  data() {
    return {
      config: {
        rating: 4.5,
        starStyle: {
          fullStarColor: '#FAAD14',
          emptyStarColor: '#E4E4E4',
        },
      },
    };
  },
};
</script>

<style lang="scss" scoped>
</style>