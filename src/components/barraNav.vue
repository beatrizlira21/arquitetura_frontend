<script setup>

</script>

<template>
<body>
    <nav class="navbar">
        <ul class="menu">
            <li><a href="#">Blog</a></li>
            <li><a href="#">Sobre</a></li>
            <li><a href="#">Descrição</a></li>
        </ul>
    </nav>
</body>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    border: none; 
}

body {
    font-family: Arial, sans-serif;
}

.navbar {
    background-color: #F0D662;
    text-align: center;
}

.menu {
    list-style: none;
    padding: 20px;
}

.menu li {
    display: inline;
    margin: 0 15px;
}

.menu a {
    text-decoration: none;
    color: #40200B;
    font-size: 18px;
    transition: color 0.3s ease;
}

.menu a:hover {
    color: #bd7a50;
}

</style>
