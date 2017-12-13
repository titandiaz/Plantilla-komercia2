<template>
  <div class="cabecera">
    <div class="logo">Ti<br>tan</div>
    <div class="carrito"></div>
    <!-- <icon class="icon-bag" name="shopping-bag" scale="1.5" ></icon> -->
    <div class="search-wrapper">
      <input class="search" type="search" placeholder="Buscar"/>
      <icon class="icon-search" name="search"></icon>
    </div>

    
  </div>
</template>

<script>
</script>

<style>
  *,
  *:before,
  *:after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  .search-wrapper {
    align-items: center;
    display: inline-flex;
    flex-flow: row-reverse nowrap;
    width: 250px;
    margin-right: 20px;
    padding-bottom: 30px;
  }
  .cabecera {
    width: 100%;
    height: 120px;
    display: flex;
    justify-content: flex-end;
    /* justify-content: space-between; */
    border-bottom: solid 1px gainsboro;
    
  }

  .logo {
    width: 70px;
    height: 70px;
    border: 3px solid #CDC5A1;
    border-radius: 50%;
    text-transform: uppercase;
    font-weight: 500;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    letter-spacing: 2px;
    position: absolute;
    left: 0;
    right: 0;
    margin: 20px auto;
  }
  .search {
    height: 40px;
    width: 100%;
    border: 1px solid gainsboro;
    border-left: 0;
    border-radius: 0 3px 3px 0;
    transition: border-color .2s ease;
    padding-left: 10px; 
  }

  .search::placeholder {
        color: gainsboro;
        font-size: 16px;
  }

  .icon-search {
    border: 1px solid gainsboro;
    border-radius: 3px 0 0 3px;
    border-right: 0;
    transition: border-color .2s ease;
    height: 40px;
    width: 30px;
    padding-left: 10px;
    color: gainsboro;

  }
</style>
