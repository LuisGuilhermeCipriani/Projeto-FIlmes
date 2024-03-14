<template>
    <header id="header_component">
        <router-link to="/" exact class="a">Filmaria</router-link>
        <button>
            <router-link to="/salvos" exact class="meusFIlmes">Salvos</router-link>
        </button>
    </header>
</template>

<script>
export default {
    name: 'Header_component'
}
</script>

<style scoped>
#header_component {
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 100%;
    height: 60px;
    background-color: brown;
}

.a {
    text-decoration: none;
    font-size: 30px;
    color: #FFF;
    cursor: pointer;
}

button {
    cursor: pointer;
    border: 0;
    background: #FFF;
    padding: 5px 15px;
    outline: none;
    border-radius: 5px;
    font-weight: bold;
    color: #000;
}

.meusFIlmes {
    outline: none;
    border-radius: 5px;
    font-weight: bold;
    color: #000;
    text-decoration: none;
}
</style>