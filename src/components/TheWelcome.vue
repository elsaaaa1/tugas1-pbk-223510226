<script setup>
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
      <DocumentationIcon />
    </template>
    <template #heading>Pendidikan</template>
    SDN 020 kampung besar seberang, mts madinatunnajah rengat, smk taruna pekanbaru, universitas islam riau
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya bermain volly

    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Tempat Tanggal Lahir</template>

    Kp.pulau 26 desember 2004
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Alamat</template>

    kota rengat kabupaten indragiri hulu
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Tentang Saya</template>

    saya suka bermain volly, mendengarkan musik, dan nonton drakor atau anime, saya anak kedua dari 3 bersaudara.
  </WelcomeItem>
</template>
