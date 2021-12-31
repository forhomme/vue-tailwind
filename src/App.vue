<template>
  <div class="divide-y divide-gray-200">
    <Header />
    <BreadCrumb />
  </div>
    <Home />
  <Footer />
</template>

<script>
import './assets/tailwind.css'
import Home from "@/components/Home";
import Header from "@/components/Header";
import Footer from "@/components/Footer";
import BreadCrumb from "@/components/BreadCrumb";

export default {
  name: 'App',
  components: {
    BreadCrumb,
    Footer,
    Header,
    Home
  }
}
</script>
