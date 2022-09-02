<template>
  <div>
    <h1>お知らせ詳細</h1>
  </div>
</template>

<script>
export default {
  asyncData ({ params }) {
    const postId = params.id

    console.log(`postID: ${postId}`)
  }
}
</script>
