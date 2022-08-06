<template>
    <div id="main-banner" :style="image">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner',
    data: function () {
        return {
            image: { backgroundImage: 'url(/assets/images/burger.jpg)' },
        };
    },
};
</script>

<style scoped>
#main-banner {
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}
#main-banner h1 {
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}
</style>
