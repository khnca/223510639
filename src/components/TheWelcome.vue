<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>History</template>

   Saya pernah magang aja di Puskesmas Daerah kota saya selama 3 bulan. 

    <br />

  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Person</template>

    Email: nadiakhalisahkhansa@student.uir.ac.id <br>
    Instagram : <a href="https://www.instagram.com/khnca_/">@khnca_</a> <br>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>

    1. Angkat Gas <br>
    2. Bersih-bersih rumah <br>
    3. Mukul maling
  </WelcomeItem>
</template>
