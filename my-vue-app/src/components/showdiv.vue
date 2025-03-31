<template>
    <div id="app">
        <div v-show="showDiv">Div tag with v-show</div>
        <div v-if="showDiv">Dive tag with v-if</div>
    </div>
</template>

<script>
export default{
    data(){
        return{
            showDiv:true,
        };
    };
};
</script>
<style scoped>
#app {
    border:black dashed 1px;
    width: 80%;
    padding: 0 20px 20px 20px;
}
#app div {
    padding :20px;
    margin: 10px;
    display: inline-block;
    font-weight: bold;
    border:solid black 1px;
}
</style>