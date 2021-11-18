<template>
  <div>
    <div class= "parents">
      <form class="main">
        <div class="form-item"> 
          <input type="text">
          
        </div>
        <div class="form-item"> 
          <input type="text">
        </div>
        <div class="form-item"> 
          <button>Войти</button>
        </div>
      </form>
   </div>
  </div>
  
</template>

<script>
export default {

}
</script>

<style scoped>

.parents {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.main{
  width: 430px;
  height: 520px;
  background-color: aqua;
  margin-top: 150px;
  border-radius:10px ;
  padding:40px 60px;

  
} 
.form-item{
  width: 100%;
  height: 100px;
}
</style>