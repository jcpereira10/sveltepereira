<script>
    import Pariente from "../componentes/Pariente.svelte";


let familia = [
    'Diego', 'Karen', 'Isabella', 'Vlado', 'Lucila'
]
</script>

<h1>Karen no se duerma</h1>

{#each familia as pinta}
<Pariente elnombre={pinta} />    

{/each }



<style>
    h1 {
        color: blue;
    }
</style>

