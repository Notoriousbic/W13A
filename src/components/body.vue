<template>
    <div class ="page-body">
        <div></div>
        <h3>meet our team</h3>
        <h3>our mission</h3>
    </div>
</template>

<script>
export default {
    name: "page-body"
}
</script>

<style scoped>
.page-body {
    display: grid;
    align-items: center;
    justify-items: center;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    height: 800px;
}
</style>