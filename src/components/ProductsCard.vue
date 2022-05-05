<template>
<div>
    <img :src="immagine" :alt="titolo">
</div>
    
</template>

<script>
export default {
    name:'ProductCard',
    data(){
        return{
             
        }
    },
    props:['immagine','titolo']

    
}
</script>

<style lang="scss" scoped>

</style>