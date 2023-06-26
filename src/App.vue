<script >

import Header from './components/Header.vue'
import SocialLink from './components/SocialLink.vue'
import About from './components/About.vue'
import Work1 from './components/Work1.vue'
import Work2 from './components/Work2.vue'
import Work3 from './components/Work3.vue'
import Work4 from './components/Work4.vue'
import Work5 from './components/Work5.vue'
import DigitalSkills from './components/DigitalSkills.vue'

import contentsData from './assets/contents.json'

export default {
  data() {
    return {
      contents: contentsData,
    };
  },
  components: {
    Header,
    SocialLink,
    About,
    Work1,
    Work2,
    Work3,
    Work4,
    Work5,
    DigitalSkills,

  },
};

</script> 

<template>
  <main>
    <Header />
    <About />
    <Work1 />
    <Work2 />
    <Work3 />
    <Work4 />
    <Work5 />
    <DigitalSkills/>
    <SocialLink />

  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
