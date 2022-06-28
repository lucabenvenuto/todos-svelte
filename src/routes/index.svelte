<script lang="ts">

    import Todos from '$lib/Todos.svelte'

    let todos: any[] = [
        {
            id: 1,
            title: 'Learn Svelte',
            description: "I'd like to learn Svelte",
            completed: false
        },
        {
            id: 2,
            title: 'Make millionaire idea',
            description: "I'd like to make a millionaire idea",
            completed: false
        },
        {
            id: 3,
            title: 'Profit',
            description: "I'd like to make profit",
            completed: false
        }        
    ]

</script>

<main>

    <Todos {todos}/>

</main>