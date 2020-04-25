<template>
  <div class="w3-mobile layout">
    <NavBar />
    <transition name="fade" appear>
      <main class="wrapper">
        <slot />
      </main>
    </transition>
    <Footer />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
import NavBar from "../components/NavBar";
import Footer from "../components/Footer";
export default {
  components: {
    NavBar,
    Footer,
  },
};
</script>
