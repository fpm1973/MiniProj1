<script setup>

import CFooter from './components/CFooter.vue'

import CQuemSou from './components/CQuemSou.vue'
import CQueFaco from './components/CQueFaco.vue'
import CHobbies from './components/CHobbies.vue'

import { ref } from 'vue';

const active = ref('COMP1')
function changeView(sVal){
  console.log(sVal);
  active.value=sVal;
  console.log(active.value)
}


</script>


<template>

  <div class="header">

      <h1>Fernando Monteiro - Miniprojeto: Single Page Application (SPA)</h1>
      

      <nav>
        
        <ul>
        <li><a @click="changeView('COMP1')">Quem Sou</a></li> 
        <li><a @click="changeView('COMP2')">Que Faco</a></li> 
        <li><a @click="changeView('COMP3')">Hobbies</a></li>
        </ul>

      </nav>
  </div>


  <div class="center-container">
    <div class="rounded-div">
      <CQuemSou v-if="active === 'COMP1'" />
      <CQueFaco v-if="active === 'COMP2'" />
      <CHobbies v-if="active === 'COMP3'" />
    </div>
  </div>


  <CFooter />
</template>


<style scoped>

.rounded-div {
  width: 70%; 
  margin-left: auto; 
  margin-right: auto; 
  
  padding: 10px;
  background-color: #f0f0f0;
  width: 1000px; 
  height: 500px; 
  background-color: #ffffffff; 
  border: 0px solid #ccc;
  border-radius: 25px; 
  padding: 20px; 
  text-align: center; 
 
  
  display: flex; 
  justify-content: center;
  align-items: center;
}


    .header {
        background-color: #3b2cc1ff; 
        padding: 15px 20px;
        color: #ffffffff;
    }

  nav {
  padding: 15px;
}
nav a {
  cursor: pointer;
  margin: 0 5px;
  text-decoration: none;
  color: #ffffffff;
}
nav a.active {
  font-weight: bold;
  color: #42b983; 
  text-decoration: underline;
}

        nav ul {
            position: absolute;
            right: 0px;
            top:50px;

            list-style: none; 
            margin: 0;
            padding: 0;
            display: flex; 
            justify-content: space-around; 
            
        }

        nav ul li {
            margin: 0 10px;
        }

        nav ul li a {
            color: #bcbab8ff;; 
            text-decoration: none; 
            font-family: Arial, sans-serif;
            font-size: 25px;
            padding: 5px 10px;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #0077b5; 
        }


</style>

