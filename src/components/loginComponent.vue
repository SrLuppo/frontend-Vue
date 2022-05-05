<template>
    <div>
        <h1>Olá Vue</h1>
        <p>Meu nome é {{ nome }} estou estudando para ser um {{ profissão}}</p>
    </div>
</template>

<script>
export default {
    name: 'loginComponent',
    data() {
        return {
            nome:"Adelano",
            profissão: "Programador"
        }
    },
}
</script>