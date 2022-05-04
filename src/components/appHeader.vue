<template>
<header>
    <nav>
        <div class="logo">
            <a href="#">
                <img src="../assets/images/dc-logo.png" alt="">
            </a>
        </div>
        
        
        <ul>
            <li v-for="(item, index) in links" :key="index" :class="{'selected': item.active}">{{item.testo}}</li>
        </ul>

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
header{
    
    margin: 0 auto;
}
ul{
    float: right;
    padding: auto 0;
    
}
li{
    list-style: none;
    display: inline-block;
    margin: 0 15px;
    
    
}
nav img{
    width: 80px;
    
}
.logo{
    float: left;
}
.selected{
    
}


</style>
