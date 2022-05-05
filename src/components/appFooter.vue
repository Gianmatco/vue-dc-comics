<template>
<footer>
    <section id="jumbotron">
    <div class="flex-container">
        <div class="flex-container-ul">
            <div>
            <ul>
                DC COMICS
                <li>characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>VIdeos</li>
                <li>News</li>
            </ul>
            <ul>
                SHOP
                <li>characters</li>
                <li>Comics</li>
            
            </ul>

        </div>
        <div>
            <ul>
                DC
                <li>characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>VIdeos</li>
                <li>News</li>
                <li>characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
            
            
            
            </ul>
        </div>
        <div>
            <ul>
                SITIES
                <li>characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
            </ul>
        </div>
        </div>
        
        
        <div class="container-img">
            <img src="../assets/images/dc-logo-bg.png" alt="">
            
        </div>
 
    </div>
    
    

</section>
<section>
    <div class="container-singup">
    <div class="container-box">
        <div>
            <p class="sing-up">SIGN-UP NOW!</p>
        </div>
        <div>
            
            <div>
                <span>follow us</span>
                <img src="../assets/images/footer-facebook.png" alt="">
                <img src="../assets/images/footer-periscope.png" alt="">
                <img src="../assets/images/footer-pinterest.png" alt="">
                <img src="../assets/images/footer-twitter.png" alt="">
                <img src="../assets/images/footer-youtube.png" alt="">
            </div>
            
         
        </div>
    </div>
    


</div>
</section>

</footer>



    
</template>

<script>


export default {
    name:'appFooter'

}
</script>

<style  scoped lang="scss">

#jumbotron{

    height: 320px;
    background-image: url(../assets/images/footer-bg.jpg);
    
    background-size: cover;
    color: white;


    ul li{
        list-style-type: none;
        color: #616a67;
    }
}

.flex-container{
    display: flex; 
    justify-content: space-between; 

   
    img{
        margin-top: -100px;
                
        

    }
}
.flex-container-ul{
    display: flex;
    
}

.container-singup{
    
    background-color: #303030;
    color: white;
    padding: 15px;

    .container-box{
        display: flex;
        justify-content: space-between;
        align-items: baseline;
    }

    .sing-up{
        margin-left:20px ;
        border: 1px solid #0483fb;
        padding: 15px;
    }
    img{
        width: 30px;
    }
}



</style>
