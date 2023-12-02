<script setup>
import api from './api.vue';
import api2 from './api2.vue';
import bas from './base.vue';

</script>

<template>

 <div class="text-center">
 
    <p class="text-blue-500 text-5xl font-medium"> Sistema Institucional de Tutoría del ITS Motul</p>                      

    
<img src="../assets/logo1.png" alt="logotipo del sitmotul" class="w-70 h-40 mx-auto mt-4">
<div class="flex flex-row">

  <div class="flex flex-col p-5 ">
    <api> </api>
  </div>
  <div class="flex flex-col p-5">
    <api2></api2>
  
  </div>
  <br>

</div>
<div class="mt-auto px-6 py-6">
    <bas></bas>
  </div>
</div>




</template>








