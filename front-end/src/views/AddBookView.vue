<template>
    <div >
        <AddBook/>
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import AddBook from '@/components/AddBook.vue'

  
  export default {
    name: 'AddBookView',
    components: {
        AddBook,
    }
  }
  </script>
  <style scoped>
  
  </style>
  