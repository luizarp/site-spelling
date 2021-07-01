<template>
  <div class="head">
    <div id="header-container" class="container">
      <div class="row wrapper">
        <div class="col logo">
          <img src="@/static/images/logo.svg" alt="" />
        </div>
        <div class="col menu">
          <ul>
            <a href="#OQueE"><li>O que é?</li></a>
            <a href="#servicos"><li>Serviços</li></a>
            <a href="#solicitarServi"><li>Solicitar serviços</li></a>
            <a href="#duvidas"><li>Dúvidas</li></a>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.head {
  position: fixed;
  z-index: 1000;
  top: 0;
  background-color: #fff;
  width: 100%;
  height: 90px;
  box-shadow: 0px 4px 5px #e5e5e5;
  font-size: 18px;
}
.wrapper {
  display: flex;
  align-items: center;
  vertical-align: middle;
}
.logo img {
  height: 40px;
}
.menu {
  height: 87px;
}
.menu ul {
  height: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin: 0;
  list-style: none;
}
.menu ul li {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.menu ul li:hover {
  border-bottom: 3px solid #ea9010;
  height: calc(100% + 3px);
  color: #ea9010;
}
.menu ul li:active {
  border-bottom: 3px solid #ea9010;
  height: calc(100% + 3px);
  color: #ea9010;
}
.menu a {
  color: #00004d;
  text-decoration: none;
}
</style>
