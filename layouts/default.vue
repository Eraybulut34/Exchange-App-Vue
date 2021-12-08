<template>
<div>
<navbar/>
  <div class="template">
    <Nuxt />
  </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    }
  },
  methods: {
   
  },
  
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@1,300&display=swap');

.template {
  background: url(/bg.jpg);
  height: 1000px;

}
.logo {
  font-size: 22px;
  font-style: normal;
  color: bisque;
  font-weight: bold;
  margin-left: 15px;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #060d50;
  margin-bottom: 50px;
  height: 45px;
  position: fixed;
  top: 0px;
  width: 100%;
  font-family: 'Raleway', sans-serif;
}

ul li {
  margin-left: 250px;
  display: inline-block;
}

ul li button {
  position: absolute;
  right: 25px;
  top: 10px;
}
</style>
