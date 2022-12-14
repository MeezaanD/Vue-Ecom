<template>
    <body>
        <h2>Comics up for Sale</h2>
        <div class="container">
            <div class="card" v-for="item in arr" :key="item">
                  <img :src="item.image" style="width: 300px;">
                  <h4>{{item.product}}</h4> 
                  <h5>{{item.studio}}</h5>
                  <p>{{item.Price}}</p>
                  <button class="btn" v-on:click="showAlert">Purchase</button>
                   
              </div>
        </div>
    </body>
    </template>
    
    <script>
    export default {
        name: 'Product',

        methods: {

        showAlert() {
            alert('Purchase successful!')
        },

        // let arr = JSON.parse(localStorage.getItem('arr')) ?
        // JSON.parse(localStorage.get('arr')) : [

        // ]
    },

        data() {
        return {
     arr : [
    {
        product: 'Batman',
        image:"https://i.postimg.cc/66fFcB4T/batman.jpg",
        studio: "DC",
        Price: 'R100'    
    },
    {
        product: 'Spider-man',
        image:"https://i.postimg.cc/fR9GxmcQ/spiderman.jpg",
        studio: "Marvel",
        Price: 'R100'    
    },
    {
        product: 'Nightwing',
        image:"https://i.postimg.cc/qqnkgSMW/nightwing.jpg",
        studio: "DC",
        Price: 'R100'    
    },
    {
        product: 'Wolverine',
        image:"https://i.postimg.cc/g2fbL41W/wolverine.jpg",
        studio: "Marvel",
        Price: 'R100'    
    }
] 
    }
    }
        
    }
    </script>
    
    <style>
    h2 {
        text-align: center;
        padding: 20px;
    }
        .container {
            display: flex;
            gap: 5rem;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
    </style>