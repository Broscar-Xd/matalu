<template>
    <div>
        <header>
        <div class="container-header">
            <div class="logo-title">
                <img src="https://i.pinimg.com/originals/37/4d/87/374d87fe1348dae07ec2a5a525942a10.jpg" alt="https://i.pinimg.com/originals/37/4d/87/374d87fe1348dae07ec2a5a525942a10.jpg">
                <h4>Registro de notas</h4>
            </div>
            <label class="icon-menu"></label>
        </div>
        </header>
    </div>
</template>

<script>
export default {
    name: 'alumnos'
}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}
header{
    width: 100%;
    height: 60px;
    background: black;
}
.container-header{
    width: 100%;
    max-width: 1200px;
}
.logo-title{
    display: flex;
}
.logo-title img{
    width: 40px;
    height: 40px;
    margin-top: 10px;
    margin-left: 10px;
}
.logo-title h4{
    color: blanchedalmond;
    font-weight: 100;
    margin-top: 10px;
    margin-left: 20px;
}
</style>