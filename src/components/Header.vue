<template>
    
<div class="row">
<div class="col-12 col-md-4">
<h1>Formularios</h1>
</div>
<div class="col-12 col-md-10">
<img  width="100" :src="url" />
</div>
</div>
<hr />
</template>


<script>

    export default{
    data:()=> ({
      url: "https://cdn.svgporn.com/logos/vue.svg?response-content-disposition=attachment%3Bfilename%3Dvue.svg",
    }),
    
    methods:{ 
      addUser(){
        console.log(this.nombre, this.edad, this.correo);
      }
    }
    
    };
    /*
    methods: {
      click(){
       this.clicks++;
      },
    },
    <div v-on:click="click" class="contador">Clicks: {{clicks}}</div>
    <ul>
    <li v-for="(valor, clave) in usuarios" :key="clave">
      {{ valor}}-{{ clave}}
    </li>
    </ul>
    <h3>Tu edad es: {{edad}}</h3>
    <h2 v-if="edad >= 18 && edad>0 && edad<100">Mayor de edad</h2>
    <h2 v-else-if="edad <18 && edad>0 && edad<100">Menor de edad</h2>
    <h2 v-else>Edad inválida</h2>
    
    <button @click="add()">Add</button>
    <button @click="dis()">Dis</button>
    export default {
      data: () => ({
         edad:17,
         usuarios:{nombre: "Pablo"},
      }),
    
      methods: {
        add(){
          this.edad++
        },
        dis(){
          this.edad--
        },
      },
    
    }*/
    </script>
    