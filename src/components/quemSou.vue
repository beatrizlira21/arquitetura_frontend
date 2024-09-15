<script setup>

</script>

<template>
  <body>
    <section class="content">
        <div class="text-box">
            <h1>Beatriz Sousa</h1>
            <p>Uma pessoa cursando pós-graduação na PUC Minas, dedicada a expandir seus conhecimentos e habilidades, sempre buscando evolução acadêmica e profissional.</p>
        </div>
      <div class="image-container">
            <img src="/src/assets/public/images/foto2.jpg" alt="Imagem Beatriz Sousa" class="profile-image">
        </div>
    </section>
</body>  
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.content {
    background-color: #F0D662;
    height: 70%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 20% 20px 20%;
    border-bottom: 5px double #BF6122
}

.text-box {
    text-align: left;
}

.text-box h1 {
    font-size: 48px;
    color: #40200B;
    margin-bottom: 20px;
}

.text-box p {
    font-size: 18px;
    color: #40200B;
    max-width: 600px;
    line-height: 1.6;
}

.image-container {
    width: 30%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.profile-image {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px double #BF6122;
}

</style>
