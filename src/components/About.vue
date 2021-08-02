<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <Logo />
      </v-col>
      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          What's next?
        </h2>

        <v-row justify="center">
          <a
            v-for="(next, i) in whatsNext"
            :key="i"
            :href="next.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ next.text }}
          </a>
        </v-row>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Social Media
        </h2>

        <v-row justify="center">
          <a
            v-for="(link, i) in socialMedia"
            :key="i"
            :href="link.href"
            class="subheading mx-3"
            target="_blank"
          >
            <v-icon>{{ link.icon }}</v-icon>
          </a>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
a {
  text-decoration: none;
}
</style>

<script>
import Logo from '@/components/Logo.vue'
  export default {
    name: 'About',
    components: {
      Logo
    },
    data: () => ({
      socialMedia: [
        {
          text: 'fb',
          icon: 'mdi-facebook',
          href: 'https://www.facebook.com/solvestack',
        },
        {
          text: 'LinkedIn',
          icon: 'mdi-linkedin',
          href: 'https://www.linkedin.com/company/solvestack',
        },
        {
          text: 'Insta',
          icon: 'mdi-instagram',
          href: 'https://www.instagram.com/solvestackofficial/',
        },
        {
          text: 'Twitter',
          icon: 'mdi-twitter',
          href: 'https://twitter.com/solvestack',
        }
      ],
      whatsNext: [
        {
          text: 'Solvestack Website',
          href: 'https://solvestack.com',
        },
        {
          text: 'Meetup Group',
          href: 'https://www.meetup.com/Solvestack-The-Software-Engineering-Mentorship-Program/',
        },
        {
          text: 'Twitch',
          href: 'https://www.twitch.tv/solvestack',
        },
      ],
    }),
  }
</script>
