<template>
  <div class="app-wrapper">
    <Layout>
      <template v-slot:left>
        <SiteAside></SiteAside>
      </template>
      <template v-slot:main>
        <router-view></router-view>
      </template>
    </Layout>
  </div>
</template>

<script lang="js">
import Layout from '@/components/Layout'
import SiteAside from '@/components/SiteAside'
export default {
  components:{
    Layout,
    SiteAside,
},
}
</script>

<style lang="less" scoped></style>
