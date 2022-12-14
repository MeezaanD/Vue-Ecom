<template>
<body>
</body>
  <router-view/>
</template>

<script>
export default {
  methods: {
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
  },
}
</script>

<style>
*,
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

</style>
