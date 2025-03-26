<template >
    <div class="container">
        <div class="row mt-4">
            <div>
                <h4>Evento Click</h4>
                <button @click="clic" class="btn btn-danger" type="button">Haga clic</button>
                <button @click="soyboton" class="btn btn-warning mx-2" type="button">Haga clic2</button>
            </div>
            <div>
                <h4>Evento Change</h4>
                <label class="input-group-text" for="">Ingresa tu Nombre</label>
                <input class="from-control mt-2" type="text" id="nombre" @change="nombreE">
                <strong>el nombre ingresado es: {{ nombre }}</strong>
            </div>
           
        </div>

    </div>
</template>
<script>
export default {
    data() {
        return{
            nombre: ''
        }
    },
    methods: {
        clic(){
            alert("gracias por darle clic")
        },
        soyboton(){
            alert("soy un boton")
        },
        nombreE(event){
            this.nombre = event.target.value
        }

    },
    
}
</script>
<style >
    
</style>