<template>
    <nav  class="navbar">
        <ul>
            <li>
                <router-link to="#home">Home</router-link>
            </li>
            <li>
                <router-link to="#about">About</router-link>
            </li>
            <li>
                <router-link to="#contact">Contact</router-link>
            </li>
        </ul>
        <div>
            P
        </div>
    </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({

})
</script>
<style scoped>
    .navbar{
        width: 100%;
        height: 78px;
        display: flex;
        justify-content: space-between;
    }
    .navbar> ul{
        padding-left :125;
        display: flex;
        align-items: center;
        list-style-type: none;
    }   
    .navbar >ul>li{
        
        margin-left: 85px;
        
    } 
    .navbar> div{
        width:72px; 
        height:72px;
        margin-top: 10px;
        margin-right: 51px;
     background-color: #a3b3d7;
     font-size: 40px;
     color: white;
     display: flex;
     align-items: center;
     border-radius: 50px;
    justify-content: center;
    }
   .navbar>ul>li>a{
        font-family: inherit;
        font-size:24px ;
        text-decoration: none;
        color: black;
        line-height: 33px;
        text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    }

</style>