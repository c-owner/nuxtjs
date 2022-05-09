<template>
  <div>
    This is Index Page.
<!--
Nuxt에서는 라우터 이동할때 NuxtLink 태그를 사용하며, 경로는 pages폴더 안에 있는 `폴더명/파일명`이 경로가 된다.
ex) apple폴더안에 apple.vue  localhost:8080/apple/apple
-->
    <NuxtLink to="/apple/apple">
      Move to "ApplePage"
    </NuxtLink>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  layout: 'AppleLayout',
}
</script>
