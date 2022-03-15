<template>
    <section class="banner-large" >
        <div id="banner-large"> </div>

    </section>
</template>

<script>
export default {
    name: 'BannerLarge',
    mounted() {
    }
}

// window.onscroll = function() {myFunction()};

// // Get the header
// var header = document.getElementById("banner-large");

// var sticky = header.offsetTop;

// function myFunction() {
//   if (window.pageYOffset > sticky) {
//     header.classList.add("sticky");
//   } else {
//     header.classList.remove("sticky");
//   }
// }

</script>

<style lang="scss">
.banner-large {
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 100;
}

/* Style the header */
.header {
  padding: 10px 16px;
  background: #555;
  color: #f1f1f1;
}

/* Page content */
.content {
  padding: 16px;
}

/* The sticky class is added to the header with JS when it reaches its scroll position */
.sticky {
  position: fixed;
  top: 0;
  width: 100%
}

</style>