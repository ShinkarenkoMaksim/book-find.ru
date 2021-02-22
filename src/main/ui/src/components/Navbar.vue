<template>
  <div class="row">
    <div class="row col-8 justify-content-start">
      <a href="#" class="btn-header">Мои книги</a>
      <a href="#" class="btn-header">Подборки</a>
      <a href="#" class="btn-header">Рецензии</a>
    </div>
    <div class="row col justify-content-end">
      <a href="#" class="btn-header btn-auth">Вход</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar"
}
</script>

<style scoped lang="scss">
.btn-header {
  text-decoration: none;
  color: $text-color;
  width: 201px;
  height: 64px;
  line-height: 64px;
  font-size: 24px;
  font-weight: 700;
  background: $btn-color;
  background-blend-mode: soft-light, normal;
  margin-right: 14px;
  -webkit-border-radius: $bdrs;
  -moz-border-radius: $bdrs;
  border-radius: $bdrs;
  -webkit-box-shadow: $bxsh;
  -moz-box-shadow: $bxsh;
  box-shadow: $bxsh;


  &:hover {
    text-decoration: none;
    color: $text-color;
  }

}

.btn-auth {
  -webkit-border-radius: 93px;
  -moz-border-radius: 93px;
  border-radius: 93px;
  margin: 0;
}
</style>
