<template>
  <div class="home" id="app">
    <h1 class="pt-5 text-white">Pokemon List</h1>
    
    <div  v-for="(data, index) in pokemons" :key="index">

      <div class="card m-auto" style="width: 18rem;">
         <img class="card-img-top" :src="data.url" alt="Card image cap">
         <div class="card-body">
           <h2>{{data.name}}</h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import axios from 'axios';
export default {
  name: 'Home',
  data() {
    return {
      pokemons:[],
    }
  },
  created(){

           axios
           .get(`https://pokeapi.co/api/v2/pokemon/${1}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        .catch((err) => {
          console.log(err)
        })

         axios
           .get(`https://pokeapi.co/api/v2/pokemon/${2}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        .catch((err) => {
          console.log(err)
        })

         axios
           .get(`https://pokeapi.co/api/v2/pokemon/${3}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        .catch((err) => {
          console.log(err)
        })

         axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        .catch((err) => {
          console.log(err)
        })

        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${5}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${5}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${6}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${7}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${8}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${9}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${10}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${11}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
        axios
           .get(`https://pokeapi.co/api/v2/pokemon/${4}`)
           .then( (response) => {
            let poke = {
              name: response.data.name,
              url: response.data.sprites.front_default,
          };
            this.pokemons.push(poke);
        })
  
  }
  
}
</script>

<style scoped>
.imagen{
  width: 80px;
  height: 80px;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #2f3640;
  min-height: 100vh;
}
</style>

