<template>
    <img class="yellow-blob" src="@/assets/Vectoryellow_blob.svg" />
    <the-navbar></the-navbar>
    <section class="intro-container">
        <h1>
            Hi!
            Nice to Meet you 
            Pranoy Here! 
        </h1>
        <img src="@/assets/intro.png" alt="Image of a Study."/>
    </section>
    <img class="grey-blob" src="@/assets/Vectorgrey_left.svg" />
    <img class="red-blob" src="@/assets/Vectorred_right.svg" />

</template>

<script lang="ts">
import { defineComponent } from 'vue';
import TheNavbar from '../UI/TheNavbar.vue';
export default defineComponent({components:{TheNavbar}});
</script>

<style scoped>
          .yellow-blob{
            position: absolute;
            top:0 ;
            left: 733px;
        }
        .grey-blob{
            position: absolute;
            left: 0;
            top:634px ;
        }
        .red-blob{
            position: absolute;
            right: 0;
            top:687px;
        }
        .intro-container{
           display: flex;
           justify-content:space-between ;
        }
        .intro-container img{
            width: 788px;
            height: 666px;
            margin-top: 110px;
            margin-right: 96px;
        }
        .intro-container h1{
            filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
            font-size: 96px;
            font-weight: 400;
            line-height: 131px;
            text-align: center;
            width: 847px;
            margin-top: 230px;
            margin-left: 106px;
        }
</style>