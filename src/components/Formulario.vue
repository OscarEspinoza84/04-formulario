<script>
    export default{
        data :()=>({
            
        }),
        methods:{
                registrarProyecto(){
                    console.log("Proyecto registrado ...")
                },
            },
    };
</script>
<template>
    <form @submit.prevent="registrarProyecto" >
        <div class="mb-3">
          <label  class="form-label">Proyecto</label>
          <input type="text" class="form-control" required/> 
        </div>
        <div class="mb-3">
          <label  class="form-label">Actividad</label>
          <select class="form-select" required>
            <option disabled selected value="">Selecione tipo de actividad ...</option>
            <option >Aplicaciones web vue</option>
            <option >Backend Service con Node.js</option>
            <option >App Movil con React Native</option>
          </select>
        </div>
        <div class="mb-3 form-check">

          <label class="form-check-label" for="exampleInputPasssword1">Urgente</label>
          <input type="checkbox" class="form-check-input">
        </div>
        <button type="submit" class="btn btn-primary">Guardar</button>
    </form>
</template>
