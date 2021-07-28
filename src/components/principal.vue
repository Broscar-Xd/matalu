<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-4">
                    <div class="container-portada">
                        <div class="capa-gradient">
                        </div>
                        <div class="container-details">
                            <div class="details">
                            
                            <p>
                                Alumnos
                                <br><br>
                                Agregar estudiantes para las materias
                            </p>
                            </div>
                            <div class="bt">
                                <a class="btn btn-primary" href="#" role="button">Ir a alumnos</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="container-portada">
                        <div class="capa-gradient">
                        </div>
                        <div class="container-details">
                            <div class="details">
                            
                            <p>
                                Notas


                                <br><br>
                                Agregar las notas de los estudiantes    
                            </p>

                            </div>
                            <div class="bt">
                                <a class="btn btn-primary" href="#" role="button">Ir a notas</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="container-portada">
                        <div class="capa-gradient">
                        </div>
                        <div class="container-details">
                            <div class="details">
                            
                            <p>
                                Materias
                                <br><br>
                                Crea nuevas materias para los alumnos
                            </p>
                            </div>
                            <div class="bt">
                                <a class="btn btn-primary" href="#" role="button">Ir a Materias</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'principal'
}
</script>

<style>
.container-portada{
    width: 100%;
    height: 400px;
    background-image: url(https://miracomosehace.com/wp-content/uploads/2020/04/recordatorio.jpg);
    background-size: 150%;
    animation: movimiento 10s infinite linear alternate;
}

.container-calculo{
    width: 100%;
    height: 400px;
    background-image: url(https://miracomosehace.com/wp-content/uploads/2020/04/recordatorio.jpg);
    background-size: 150%;
    animation: movimiento 10s infinite linear alternate;
}
@keyframes calculo {
    from{
        background-position: top left;
    }to{
        background-position: top right;
    }
    
}
.container-details{
    width: 100%;
    min-width: 60px;
    position: relative;
    margin: auto;
    
}
.container-details p{
    font-family: sans-serif;
    text-align: center;
}
.details{
    width: auto;
    min-width: 550px;
    position: relative;
    top: 105px;
    color: black;
}
.bt{
    width: 300px;
    min-width: 550px;
    position: relative;
    top: 105px;
    color: black;
}
</style>