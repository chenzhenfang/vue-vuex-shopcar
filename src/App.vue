<template>
    <div id="app">
        <h3>Vuex购物车demo</h3>
        <!-- 商品的列表 -->
        <product></product>
        <!-- 购物车的列表 -->
        <car></car>
        <!-- 小记 -->
        <result></result>
    </div>
</template>

<script>
    import product from './components/product';
    import car from './components/car';
    import result from './components/result';
    
    export default {
        name: 'app',
        components: {
            product,
            car,
            result
        }
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }
</style>
