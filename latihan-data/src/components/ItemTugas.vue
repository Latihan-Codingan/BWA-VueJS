<template>
    <div>
        <div class="form-check">
            <input class="form-check-input" onclik="" type="checkbox" id="defaultCheck1">
            <label class="form-check-label item" v-bind:class="{'item-completed':tugasSaya.isDone}"
                for="defaultCheck1">{{ tugasSaya.namaTugas }}</label>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'ItemTugas',
        props:["tugasSaya"]
    }
</script>

<style scoped>

</style>