<script setup>
import experiment from '../mds/experiment_libero.mdx';
</script>

<template>
  <div v-animate-onscroll="'animated fadeInUp'">
    <el-divider />

    <el-row justify="center">
        <el-col :xs="28" :sm="24" :md="20" :lg="16" :xl="12">
            <h1 class="title">Experiment</h1>
            <el-image src="./libero_results.png" class="caption-img" fit="cover" />
            <experiment class="caption-text" />
        </el-col>
    </el-row>

  </div>
</template>

<style scoped>

.title {
  margin-bottom: 20px;
}

.caption-img {
    width: 80%;
    margin: 0 10%;
}

.caption-text {
    margin: 20px 0;
}

</style>