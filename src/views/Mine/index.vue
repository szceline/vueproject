<template>
    <div id="main">
        <Header title="个人中心"/>
        <div id="content">
            <Login />
        </div>
        <TabBar />
    </div>
  </template>
  
  <script>
    import Header from '@/components/Header';
    import TabBar from '@/components/TabBar';
    import Login from '@/components/Login';
    export default {
        name:'Mine',
        components:{
            Header,
            TabBar,
            Login
        }
    }
  </script>
  <style scoped>
  </style>