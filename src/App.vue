<template>
<div id="app">
  <p>{{items[0].name}}</p>
</div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// export default  {
//   data () {
//     return {
//       message: 'こんにちは'
//     }
//   }
// }

var items = [
  {
    name: '鉛筆',
    price: 300,
    quantity: 0
  },
  {
    name: 'ノート',
    price: 400,
    quantity: 0
  },
  {
    name: '消しゴム',
    price: 500,
    quantity: 0
  }
]

var vm = new Vue({
  el: '#app',
  data: {
    items: items
  }
})

window.vm = vm
</script>

<style>

</style>
