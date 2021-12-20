<template>
    <Header>
        <h1>{{title}}</h1>
        <Button text="Add Task" color="green"/>
    </Header>
</template>

<script>
import Button from './Button'

export default {
    name: 'Header',
    props: {
        title: String,
    }, 
    comments: {
        Button
    }
}
</script>
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
