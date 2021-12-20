<template>
<div>
    <div :key="task.id" v-for="task in tasks" >
        <Task :task="task" />
    </div>
</div>
</template>

<script>
import Tast from './Task'
export default {
    name: 'Tasks',
    props: {
        tasks: Array
    },
    components: {
        Task,
    }
}
</script>
