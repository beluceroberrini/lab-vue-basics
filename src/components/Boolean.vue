<template>
    <div>
        <button  @click="toggle" class="bgA" > CLICK ME!         
        </button>
        <h1 v-if="positivo">ENTONCES ES TRUE</h1>
        <h2 v-else>ESTE ES FALSE</h2>
        
    </div>
</template>

<script setup>
import {ref} from 'vue';

const positivo = ref(true);

const toggle = () =>{
    positivo.value = !positivo.value


}



</script>

<style scoped>
.bgA{
    background-color: #5486;
}

.bgB{
    background-color: aquamarine;
}

</style>