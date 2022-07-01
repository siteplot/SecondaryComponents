<template>
    <button class="border-transparent bg-primary-100 shadow-md my-auto flex justify-center py-2 px-2 border text-sm font-medium rounded-md transition duration-150 ease-in-out hover:bg-primary-300 hover:border-primary-700 active:bg-primary-700 text-white transition duration-150 ease-in-out">
        {{widgetData}}
    </button>
</template>
<script>
    module.exports = {
        data() {
            return {
                widgetData: 'lkjfasd;lkfjasd;n'
            }
        },
        created(){
            console.log('created')
        },
        mounted() {
          	console.log('hio')
        }
    }
</script>