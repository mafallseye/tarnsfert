<template>
  <footer class="footer footer-center p-4  bg-base-100 text-base-content 
            text-center
           
             fixed
           
             bottom-0
            ">
    <div>
      <p>&copy;{{ year }}|All right reserved by MAXDEV</p>
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
