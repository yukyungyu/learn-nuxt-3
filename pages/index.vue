<template>
  <q-page padding>
    <div class="q-my-xl text-center">
      <div class="text-h4">All Courses</div>
      <p class="q-mt-sm text-grey-8">
        웹 개발 입문부터 실전까지 학습해보세요.
      </p>
    </div>
    <div class="row q-col-gutter-lg">
      <div v-for="n in 3" :key="n" class="col-12 com-md-4 col-sm-6">
        <CourseCard />
      </div>
    </div>
</q-page>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>

</style>