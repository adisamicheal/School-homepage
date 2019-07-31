<template>
<div>
    <aside class="app-sidebar">
    <div class="d-flex">
      <form>
          <input class="form-control search-box" type="search">
      </form>
      <img src="../assets/not.png" class="not">
      <p>Ukauwa David </p>
      <p>dukauwa@du.com</p>
      <img src="../assets/Ellipse.png" class="ellipse"> 
    </div>
    <div class="logo-part">
      <img src="../assets/crestschool.png"> <p class="name">Handmaid's International</p>
    </div>
    
      <ul class="categories-list">
        <li class="category" v-for="category in categories" :key="category">
          <router-link class="categorys" to="/">{{ category.charAt(0).toUpperCase() + category.slice(1) }}</router-link>
        </li>
      </ul>
      <hr class="line">
    </aside>
    
</div>
</template>

<script>

export default {
  name: 'Sidebar',

  data() {
    return {
      categories: [
        "dashboard",
        "students",
        "employees",
        "guardian",
        "attendance",
        "finance",
        "subject",
        "batches",
        "report card",
        "sms",
        "events",
      ]
    }
  }
}
</script>

<style>

.logo-part{
  background-color: #ffffff;
  height: 70px;
}
.name{
  color: #000000;
  margin-top: -30px;
  padding-left: 40px;
}

.categories-list {
  padding: 3em 2em;
  list-style: none;
  margin: 0;
}

.category {
  padding: 0.5em 1em;
  margin-bottom: 0.5em;

}
.categorys{
   color: #fff; 
}
.categorys:hover{
  background-color: #fff;
}

.app-sidebar {
  background: linear-gradient(136.25deg, #1B75BB 0%, #00ADEE 100%);
  height: 100%;
  color: #ffffff;
  width: 265px;
}

.line{
  color: #ffffff;
}
.form-control{
  background: #FFFFFF;
  border: 1px solid rgba(189, 189, 189, 0.25);
  box-sizing: border-box;
  box-shadow: 0px 2px 9px rgba(196, 196, 196, 0.11);
  border-radius: 3px;
  width: 796px;
  height: 38px;
  margin-left: 290px;
  margin-top: 28px;
}
.not{
  height: 20px;
  width: 17px;
}
.ellipse{
  width: 35px;
  height: 35px;
}
</style>