<template>
 <div class="grid grid-cols-4 mt-5 gap-4  static" >
      
    <div class="text-left p-3">
 <strong> NORBEY PINZON IBAÑEZ</strong>
 <br>
  Edad:37
  <br>
  Ubicacion: Bogota
  <br>
  Profesion: 
  <br>
  Nivel de educación: Especialización
  <br>
  Fuentes de empleo: El empleo
</div>
    <div class="items-start text-left p-2.5">
<strong> Dispapeles </strong>
<br>
Epecialista de producto
 <br>
may, 2020(5 meses)
 <br>
  <br>
<strong> Dispapeles/consumo masivo </strong>
 <br>
Especialista de producto
 <br>
Dato no ingresado (1 año y 3 meses)
    </div>
      
    <div class="text-left p-2.5">
    Telecomunicaciones
    <br>
    Venta presencial / Comercio al por menor y por mayor / Grandes superficies
     <br>
     Ventas
      <br>
      Supervisor / Administrador
       <br>
       Planes de telefonia, internet o television
        <br>
        Tecnologia
    
    </div>
     <div class="text-left p-16">
       
       <strong> Nombre del cuestionario para sistemas utiles </strong>


     </div>
</div>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
