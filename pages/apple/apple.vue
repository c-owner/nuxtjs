<template>
  <div>
    <!--
    컴포넌트 임포트하는 방법 : "폴더명+파일명" 조합을 이룬다.
    apple/World.vue 일 때 <AppleWorld />로 사용할 수 있으며 별도의 import를 작성하지 않아도 된다.
     -->
    <AppleWorld/>
  </div>
</template>

<script>
export default {
  name: 'ApplePage',
  /*
Layout 임포트하는 방법 : 이벤트 사이클에 layout: '파일명",
Layout안에서는 <Nuxt />라는 태그를 작성해 화면에 Page 또는 Component를 렌더링(표시)하겠다는 태그를 사용한다.
<Nuxt />를 사용하지 않으면 무조건 Layout 템플릿만 화면에 표시되기 때문임.

  */
  layout: 'AppleLayout',
}
</script>
