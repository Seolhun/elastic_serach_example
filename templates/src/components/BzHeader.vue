<template>
    <header style="background-color: rgb(255,198,32);">
        <div class="text-logo">{{msg}}</div>
        <ul class="header-operations">

        </ul>
    </header>
</template>

<script>
    export default {
        name: 'bz-header',
        data() {
            return {
                msg: 'Buzzni Searching Project'
            }
        }
    }
</script>

<style>
    header {
        height: 70px;
        position: absolute;
        width: 100%;
        top: 0;
        left: 0;
        padding: 0 20px;
        z-index: 1;
        box-sizing: border-box;
    }

    .text-logo {
        display: inline-block;
        vertical-align: middle;
        border-style: none;
        position: relative;
        top: 26px;
        right: -20px;
        font-size: 25px;
        color: white;

    }

    .meta {
        color: #7e95c5;
        width: 200px;
        display: block;
        margin: -5px 0 0 225px;
        font-weight: 700;
        font-size: 0.3rem;
    }
</style>