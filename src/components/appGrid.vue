<template>
<main>
    <div class="container">
        <h3> -- Content goes here -- </h3>
    </div>
    <div class="container-img-text">
        <div>
             <img src="../assets/images/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
        </div>
         <div>
            <img src="../assets/images/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
        </div>
         <div>
             <img src="../assets/images/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
        </div>
         <div>
             <img src="../assets/images/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
        </div>
         <div>
             <img src="../assets/images/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
        </div>
       

    </div>
    
</main>

</template>

<script>

export default {
    name:'appGrid',
    data(){
        return{
            shop:[
                {
                    testo:"digital comics",
                    img:"comics-digital-comics.png",
                    link:"",
                    active:"false",
                },
                {
                    testo:"dc merchandise",
                    img:"comics-merchandise.png",
                    link:"",
                    active:"false",
                },
                {
                    testo:"subscription",
                    img:"comics-subscriptions.png",
                    link:"",
                    active:"false",
                },
                {
                    testo:"comic shop locator",
                    img:"comics-subscriptions.png",
                    link:"",
                    active:"false",
                },
                {
                    testo:"dc power visa",
                    img:"dc-power-visa.svg",
                    link:"",
                    active:"false",
                }
            ]
        }
    }
    
}
</script>

<style  scoped lang="scss" >

.container{
    height: 120px;
    color: white;
    background-color: #1c1c1c;
    display: flex;
    align-items: center; 
}
img{
    width: 70px;

}
.container-img-text{
    
    height: 200px;
    background-color: #0282f9;
    color: white;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    
    

}



</style>
