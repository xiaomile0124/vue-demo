<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'

import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <h1>this is home page</h1>
</template>
