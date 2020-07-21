<template>
    <div id="app">
        <img src="../assets/logo.png">
        <div>
            <p style="font-size: 40px">
                欢迎使用利德热处理管理加工系统
            </p>
            <el-button>进入演示程序</el-button>
        </div>
        <HelloWorld msg="利德热处理加工系统"/>
    </div>

</template>

<script>
    //import HelloWorld from './components/HelloWorld.vue'

    export default {
        name: 'app',
        /*components: {
          // HelloWorld
        }*/
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
