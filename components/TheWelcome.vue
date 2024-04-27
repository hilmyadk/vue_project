<script setup>
import WelcomeItem from './WelcomeItem.vue'
import BioIcon from './icons/IconDocumentation.vue'
import SkillIcon from './icons/IconTooling.vue'
import ExperienceIcon from './icons/IconEcosystem.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <BioIcon />
    </template>
    <template #heading>Biodata Diri</template>

    Perkenalkan nama saya Muhammad Hilmy Andika, saya lahir di Pekanbaru, Riau. Saya merupakan mahasiswa Universitas Islam Riau angkatan 22 dari jurusan Teknik Informatika.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SkillIcon />
    </template>
    <template #heading>Skill & Kemampuan</template>

    Dalam hal skill dan kemampuan sebenarnya saya belum memiliki kedua hal itu ketika saya pertama kali ngoding, namun seiring berjalannya waktu sampai sekarang saya sudah belajar banyak hal tentang codingan.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ExperienceIcon />
    </template>
    <template #heading>Pengalaman yang pernah dimiliki</template>

    Saya memiliki pengalaman dalam bekerja sama secara tim yaitu ketika membuat tampilan UI suatu aplikasi atau website. <br>
    Salah satu contohnya proyeknya yaitu membuat tampilan UI untuk aplikasi Mobile Banking.
  </WelcomeItem>
</template>
