<template>

    
        <div class="card">
            <img :src="immagine" :alt="titolo">
            <p>{{titolo}}</p>
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




.card{
    
    flex-basis: 15%;
    margin: 20px auto;
    
    
}

    


img{
    width: 150px;
    height: 150px;
    
        
        
}



</style>