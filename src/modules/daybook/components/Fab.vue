<template>
    <button class="btn btn-primary">
        <li class="fa fa-2x"
            :class="icon"></li>
    </button>
</template>

<script>

// valor de fault fa-plus
export default {

    props:{
        icon:{
            type: String,
            default: 'fa-plus'
        }
    }


}
</script>



<style lang="scss" scoped>
    button{
        border-radius: 100%;
        bottom: 20px;
        height: 60px;
        position: fixed;
        right: 20px;
        width: 60px;
    }
</style>