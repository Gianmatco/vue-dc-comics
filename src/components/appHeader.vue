<template>
<header>
    <nav>
        <img src="../assets/images/dc-logo.png" alt="">
        <ul>
            <li v-for="(item, index) in links" :key="index">{{item.testo}}</li>
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


<style lang="scss" scoped>

</style>
