<script >

import Header from './components/Header.vue'
import SocialLink from './components/SocialLink.vue'
import About from './components/About.vue'
import Work from './components/Work.vue'
import Work2 from './components/Work2.vue'
import Work3 from './components/Work3.vue'
import Work4 from './components/Work4.vue'
import Work5 from './components/Work5.vue'

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
    Work,
    Work2,
    Work3,
    Work4,
    Work5,

  },
};

</script> 

<template>
  <main>
    <Header />
    <About />
    <Work />
    <Work2 />
    <Work3 />
    <Work4 />
    <Work5 />
    
    <div id="social-links" class="row">
      <ul>
        <li v-for="link in contents.social_links" :key="link.id">
          <SocialLink 
            :id="link.id"
            :name="link.name"
            :url="link.url"
          />
        </li>
      </ul>
    </div>

   <Footer />
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
