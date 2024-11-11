<script>
export default {
  mounted() {
    this.$refs.scrollableContainer.addEventListener('scroll', this.handleScroll);
  },
  methods: {
    handleScroll() {
      // Perform actions based on scroll position
      console.log(this.$refs.scrollableContainer.scrollTop);
    },
  },
};
</script>
<template>
  <div ref="scrollableContainer">
    <!-- Your content here -->
  </div>
</template>
