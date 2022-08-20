<template>
  <footer class="footer footer-center p-4 bg-base-100 text-base-content">
    <div>
      <p>&copy;{{ year }}|All right reserved by AXETAG SAS</p>
    </div>
  </footer>
</template>

<script>
export default {
  setup() {
    const year = new Date().getFullYear();
    return {
      year,
    };
  },
};
</script>

<style></style>
