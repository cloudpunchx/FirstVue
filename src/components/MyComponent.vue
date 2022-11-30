<!-- 3 STEPS FOR COMPONENTS SEE BELOW -->

<!-- used vbase-css shortcut for this, could also choose SCSS instead if I want to use SCSS -->
<template>
    <div>
        <h1>Hello Components!</h1>
    </div>
</template>

<script>
// This is what allows us to use this component in other places
// Mark said he never likes to use back ticks because they can mess things up
    export default {
        name : "MyComponent",
    }
</script>

<style scoped>

</style>