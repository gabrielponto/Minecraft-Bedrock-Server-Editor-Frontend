<template>
    <div class="worlds">
        <table class="table">
            <thead>
                <tr>
                    <th>Nome</th>
                    <th>Criado em</th>
                    <th>Ativo</th>
                    <th>Ativar</th>
                </tr>
            </thead>
            <tbody>
                <tr v-for="world in worlds" :key="world.id">
                    <td>{{ world.name }}</td>
                    <td>{{ world.date }}</td>
                    <td>{{ world.active }}</td>
                    <td><button class="btn btn-primary">Ativar</button></td>
                </tr>
            </tbody>
        </table>
    </div>
</template>
<script>
    export default {
        name: "Worlds",
        data: function() {
            return {}
        },
    };
</script>
<style scoped>

</style>

