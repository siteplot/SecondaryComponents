<style>
.test{
    background: red !important;
}
</style>
<template>
  <button type="button" class="test inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
    {{ buttonText }}
  </button>
</template>
<script>
 module.exports = {
    data() {
       return { 
        buttonText: 'Button Text'
       }
    },
    mounted(){
        console.log('test log');
    }
 }
</script>