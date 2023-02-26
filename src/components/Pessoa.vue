<template>
    <div>
        <h2>Esta é a descrição da pessoa:{{ nome }} </h2>
        <Info/>
        <Formulario/>
    </div>
</template>
<script>
   import Info from './Info';
   import Formulario from './Formulario.vue';
   export default {
        name: 'Pessoa',
        components: {
          Info,
          Formulario
        },
        data() {
            return {
                nome: 'Alzevir'
            }
        }
   }
</script>