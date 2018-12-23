<template>
   <div>{{message}}</div> 
</template>

<script>
export default {
    props: {
        message: String
    }
};
</script>

<style lang="scss" scoped>
div {
    font-size: 2rem;
}
</style>

