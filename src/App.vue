<template>
  <Navbar></Navbar>
 <center>  <Header></Header> </center>
 <br>

 <center><About></About></center>
 <Skill></Skill>
<Contact></Contact>
 <Footer></Footer>
</template>

<script>
import Header from './components/Header.vue';
import Navbar from './components/Navbar.vue';
import About from './components/About.vue';
import Skill from './components/Skill.vue';
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue';

export default {
  components : {
    Header,
    Navbar,
    About,
    Skill,
    Contact,
    Footer
  }
}
</script>