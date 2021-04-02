<template>
    <table class="table">
        <thead>
            <tr>
                <th v-for="column in columns" :key="column.key">{{ column.label }}</th>
            </tr>
        </thead>
        <tbody>
            <tr v-for="column in data" :key="column.key">
                <td v-for="row in column.rows" :key="row.key">
                    {{ row.value }}
                </td>
            </tr>
        </tbody>
    </table>
</template>
<script>
export default {
    name: 'Table',
    props: {
        columns: {
            type: Array,
            default: []
        },
        data: {
            type: Array,
            default: []
        }
    }
}
</script>
<style scoped>

</style>
