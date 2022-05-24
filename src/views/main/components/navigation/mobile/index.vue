<template>
  <div>移动端navigation</div>
</template>

<script setup>
import { getCategory } from '@/api/category'

const getCategoryDate = async () => {
  const res = await getCategory()
  console.log(res)
}

getCategoryDate()
</script>

<style lang="scss" scoped></style>
