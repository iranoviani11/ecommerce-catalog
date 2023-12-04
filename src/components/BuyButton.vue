<template>
    <div :class="{ ButtonWoman: woman, ButtonMan: man }">
        <button>Buy now</button>
    </div>
</template>
<script>
export default {
    name: "BuyButton",
    props: ["woman", "man"],
};
</script>
<style scoped>
.ButtonWoman button {
    border: 2px solid #720060;
    background-color: #720060;
    font-family: "Prompt", sans-serif;
    color: white;
    padding: 10px;
    margin-right: 20px;
    margin-top: 20px;
    width: 90%;
    border-radius: 5px;
}

.ButtonMan button {
    border: 2px solid #002772;
    background-color: #002772;
    font-family: "Prompt", sans-serif;
    color: white;
    padding: 10px;
    margin-right: 20px;
    margin-top: 20px;
    width: 90%;
    border-radius: 5px;
}
</style>