<template>
    <div class="foot text-center h-auto">
        <button class="shadow"><img src="@/assets/img/btn-icon.png" class="m-auto btn-icon" /></button>
    </div>
</template>
<script>
export default {
    name: 'Footer'
}
</script>
<style>
    .foot {
        height: 33px;
    }
    button {
        position: relative;
        top: 0;
        height: 68px;
        width: 68px;
        border-radius: 50%;
        color: #fff;
        font-size: 25px;
        background: #38D39F;
        transition: ease-in-out 0.1s;
    }
    button:hover {
        background: rgb(47, 184, 138);
    }
    button:active {
        -moz-outline-radius: 50%;
    }
    .btn-icon {
        max-height: 28px;
        max-width: 28px;
    }
</style>
