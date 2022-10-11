<template>
    <div v-for="item in data" >
        <div>{{item.title}}</div>
        <br>
        <div>{{item.body}}</div>
        <br>
        <div>{{item.image}}</div>
    </div>
</template>

<script setup>
const data = [
    {
        title:'Simplify',
        body:'UI Design & App Development',
        image:'ACA VA UNA IMAGEN'
    },
    {
        title:'Dashcoin',
        body:'Web Development',
        image:'ACA VA OTRA IMAGEN',
    },
    {
        title:'Vectorify',
        body:'User Experience Design',
        image:'ACA VA OTRA IMAGEN',
    }
]

</script>


<style scoped>
</style>