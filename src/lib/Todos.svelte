<script lang="ts">

    import Todo from "./Todo.svelte";

    export let todos: any[] = [];

</script>

<main>

    <div class="body">        
        {#each todos as todo (todo.id)}
            <div class="element">
                <Todo {...todo}/>
            </div>
        {/each}
    </div>

</main>

<style>

    .body {
        position: relative;
        max-width: max-content;
    }

    .element {
        border-style: dashed;
    }
</style>