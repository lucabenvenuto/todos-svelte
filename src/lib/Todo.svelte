<script lang="ts">
    export let title: string = '';
    export let description: string = '';
    export let done: boolean = false;
</script>

<main>
    <h1>{title}</h1>
    <p>{description}</p>
    <p>Completed: {done ? 'yes' : 'no'}</p>
</main>
