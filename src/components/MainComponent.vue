<template>
    <main id="MainComponent"> 
        <section class="container-main">
            <div class="card" > 
            <CardComponent class="item" :data="card" v-for="card in data" :key="card.thumb"/>
            </div>
        </section>
    </main>
 
</template>

<script>
   import CardComponent from '@/components/CardComponent.vue';
export default {
name: 'MainComponent',
props:{
    data:Array,
},
components:{
    CardComponent,
   
},
}
</script>

<style scoped lang="scss">
$zero-auto: 0 auto;
    main{
        width: 100%;
        color: white;
        background-color: black;
        margin: $zero-auto;
    }
    .container-main{
        margin: $zero-auto;
        max-width: 1200px;
    }
    .card{
        display: flex;
        flex-wrap: wrap;
    }
    .item{
        width: calc(100% / 4);
       
    }
</style>