<template>
    <div class="wrapper">
      <h1>Приложение</h1>
      <p>Информация</p>
      <input type="text" placeholder="Введите ID">
      <button>Отправить</button>
    </div>
</template>

<style scoped>
.wrapper {
  width: 900px;
  height: 500px;
  border-radius: 50px;
  padding: 20px;
  background-color: #f5f5f5;
  text-align: center;
}
.wrapper h1 {
  margin-top: 50px;
}
.wrapper p {
  margin-top: 20px;
}
.wrapper input {
  margin-top: 30px;
  background: transparent;
  border: 0;
  border-bottom: 1px solid rgba(105, 120, 141, 0.27);
  color: black;
  padding: 5px 8px;
  outline: none;
}
.wrapper input:focus {
  border-bottom: 1px solid rgba(194, 197, 201, 0.27);
}
.wrapper button {
  background: #e3bc4d;
  color: black;
  border-radius: 10px;
  border: 2px solid #b99935;
  padding: 5px 5px;
  margin-left: 20px;
  cursor: pointer;
  transition: transform 500ms ease;
}
.wrapper button:hover {
 transform: scale(1.1) translateY(-5px);
}
</style>

<script>
</script>