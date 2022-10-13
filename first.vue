<template><div> Hello {{ name }}</div>
    
</template>
<script>
    export default{
        name: 'first',
        data(){
            return{
                greet: "hello",
                name: 'Ayush Jain',
            };
        },
    };
</script>
<style>
   #name{
       color: red;
       text-align: center;
       margin-top: 60px;
   }
</style>