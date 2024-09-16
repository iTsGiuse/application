<script>
    export default{
        name:'Info'
    }
</script>

<template>
    <div class="container my-5">
        <div class="row mb-4">
            <div class="col-12">
                <h1>Su di me</h1>
            </div>
        </div>
        <div class="row align-items-center">
            <div class="col-12 col-md-4 mb-4 mb-md-0">
                <a class="navbar-brand d-block">
                    <img src="https://avatars.githubusercontent.com/u/139480769?v=4" alt="Foto profilo" class="img-fluid rounded-circle">
                </a>
            </div>
            <div class="col-12 col-md-8">
                <p class="fs-5">
                    Sono <b>Giuseppe Amato</b>, un professionista orientato al dettaglio e efficace nel lavoro di squadra, costantemente alla ricerca di sfide per migliorare 
                    le mie abilità e contribuire al successo dei progetti aziendali. Oltre alla mia passione per la programmazione, mi dedico attivamente
                    a diverse attività creative: pratico teatro, frequento la palestra, ballo hip-hop e suono la chitarra. Queste esperienze non solo arricchiscono il
                    mio approccio al lavoro, ma mi hanno anche insegnato disciplina, creatività e capacità di adattamento, competenze che applico nel
                    mondo del software.
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">

    .profilo{
        display: inline-block;
        width: 100px;
        height: 100px;
                    
        img{
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover; 
        }
    }

</style>
