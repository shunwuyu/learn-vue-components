<template>
  <div class="search">
  搜索结果
  <hr/>
  {{this.$route.query.searchData}}
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Search',
  components: {
    
  },
  mounted() {//生命周期 
    console.log(this.$route.query.searchData);
  },
}
</script>
