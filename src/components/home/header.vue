<template>
    <div>
        <div id="headers">
            <div class="headerButton">ssss</div>
            <div class="headerButton">ss</div>
            <div class="headerButton">sssss</div>
            <div class="headerButton">ssss</div>
            <div class="headerButton">ssss</div>
        </div>
    </div>

</template>

<script>
    export default {
        name: "theHeader"
    }
</script>

<style scoped>
    #headers{
        width: 100vw;
        height: 80px;
        display: flex;
        background-color: black;
        line-height: 80px;
    }
    .headerButton{
        color: white;
        font-size: 1.225rem;
        padding: 0 10px;
        display: block;
        margin: 0 30px;
        cursor:pointer
    }
    .headerButton:hover{
        border: #c53437 0 solid;
        border-bottom-width: 3px;
    }
</style>
