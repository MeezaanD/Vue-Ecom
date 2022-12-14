<template>
    <body>
        <div class="contact">
            <div class="container">
                <form>
                  <label for="fname">FirstName</label>
                  <input type="text" id="fname" name="firstname" placeholder="Your name.." v-model="name">
              
                  <label for="lname">LastName</label>
                  <input type="text" id="lname" name="lastname" placeholder="Your last name.." v-model="surname">
              
                  <label for="favorite">Favorite Superhero</label>
                  <select id="favorite" name="fbiscuit" v-model="hero">
                    <option value="Batman">Batman</option>
                    <option value="Spiderman">Spiderman</option>
                    <option value="Nightwing">Nightwing</option>
                    <option value="Wolverine">Wolverine</option>
                  </select>
              
                  <label for="subject">Subject</label>
                  <textarea id="subject" name="subject" placeholder="Write something.." v-model="message" style="height:200px"></textarea>
              
                  <button type="submit" v-on:click.prevent="submit">Submit</button>
                </form>
              </div>
        </div>
    </body>
</template>
<script>
export default {
  name: 'Contact',
  methods: {
    submit(){
 alert(`${this.hero}, is the favourite hero of ${this.name} ${this.surname} and he says that ${this.message}`)
    }  
  },
}

</script>
<style>
input[type=text], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
  }
  
  input[type=submit] {
    background-color: aqua;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  input[type=submit]:hover {
    background-color: yellow;
  }
  
  .container {
    border-radius: 5px;
    padding: 20px;
  }
</style>