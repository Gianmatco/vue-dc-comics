<template>
<header>
    <nav class="flex-container">
        <div class="logo">
            <a href="#">
                <img src="../assets/images/dc-logo.png" alt="">
            </a>
        </div>
        
        <div class="nav-option">
            <ul>
                <li v-for="(item, index) in links" :key="index" :class="{'selected': item.active}">{{item.testo}}</li>
            </ul>
        </div>
        

    </nav>

    

</header>
</template>

<script>


export default {
    name: 'appHeader',
    data(){
        return{
            links:[
                {
                    testo:"characters",
                    link:"",
                    active:"false",
                },
                {
                    testo:"comics",
                    link:"",
                    active:"false",
                },
                {
                    testo:"movies",
                    link:"",
                    active:"false",
                },
                {
                    testo:"tv",
                    link:"",
                    active:"false",
                },
                {
                    testo:"games",
                    link:"",
                    active:"false",
                },
                {
                    testo:"collectibles",
                    link:"",
                    active:"false",
                },
                {
                    testo:"videos",
                    link:"",
                    active:"false",
                },
                {
                    testo:"fans",
                    link:"",
                    active:"false",
                },
                {
                    testo:"news",
                    link:"",
                    active:"false",
                },
                {
                    testo:"shop",
                    link:"",
                    active:"false",
                }
            ]
        }
    }
    
}
</script>


<style scoped lang="scss">

.flex-container{
    display: flex;
    align-items: center;
    justify-content: space-between;

}


li{
    list-style: none;
    display: inline-block;
    margin: 0 15px;
    
    
}
nav img{
    width: 80px;
    
    
}




</style>
