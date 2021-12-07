<template lang="pug">
#about
  b-container
    b-row
      b-col(cols='12')
        p
          | 網頁設計及維護：23 林筑嫻
          br
          | 最近更新日期：{{ date }}
</template>

<script>
export default {
  data () {
    return {
      date: new Date().toLocaleDateString()
    }
  }
}
</script>
