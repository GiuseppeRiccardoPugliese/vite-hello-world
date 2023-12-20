<script>
export default {
    name: 'AppHero'
}
</script>

<template>
    <div class="jumbotron">
        <img src="../assets/jumbo.png" alt="Descrizione dell'immagine">
        <h1>Benvenuto!!</h1>
        <a href="#" class="btn">Maggiori Informazioni</a>
    </div>
</template>

<style scoped>
.jumbotron {
    background-color: #f8f9fa;
    text-align: center;
    padding: 50px 0;
}

.jumbotron img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    margin-bottom: 20px;
}

.jumbotron h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #6c757d;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    font-size: 1.2em;
    text-decoration: none;
    background-color: #007bff;
    color: #fff;
    border-radius: 5px;
}

.btn:hover {
    background-color: #0056b3;
}
</style>
