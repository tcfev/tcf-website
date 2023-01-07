<template>
  <div>
    <Hero
      title='Transnational Community Federation'
      sub-title='We are a group of people who believe in taking action and changing the world into a better place. We are just starting and are happy to welcome new members who want to build TCF with us and develop the projects. Check our constitution and become a member now.'
      buttons
    />
    <Projects />
    <JoinUs />
    <Footer />
  </div>
</template>

<script>
import Navbar from '../components/layouts/navbar'
import Hero from '../components/sections/Hero'
import Projects from '../components/sections/projects'
import JoinUs from '../components/sections/joinUs'
import Footer from '../components/layouts/footer'
export default {
  name: 'IndexPage',
  components: { Footer, JoinUs, Projects, Hero, Navbar },
}
</script>
