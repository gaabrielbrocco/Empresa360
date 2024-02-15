<template>
    <div>
        <h5>Compondente Opções</h5>
        <p>Poderíamos recuperar as opções do serviço id {{id}}</p>
    </div>
</template>

<script>
export default {
    name: 'Opcoes',
    props: ['id'],
    created() {
        //console.log('Parâmetro via props', this.id)
    },
    //beforeRouteUpdate(to, from, next) {
    beforeRouteUpdate() {
        console.log('Guarda de componente beforeRouteUpdate')
    }
}
</script>