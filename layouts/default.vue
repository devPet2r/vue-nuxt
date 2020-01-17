<template>
  <div>
    <p>
      <!-- 네비게이션을 위해 router-link 컴포넌트를 사용합니다. -->
      <!-- 구체적인 속성은 `to` prop을 이용합니다. -->
      <!-- 기본적으로 `<router-link>`는 `<a>` 태그로 렌더링됩니다.-->
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/abc">Abc</router-link>
    </p>
    <nuxt />
  </div>
</template>

<style>
</style>

