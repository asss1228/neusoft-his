<template>
    <el-container>
        <el-header style="background-color: #409EFF; color: white; font-size: 20px; font-weight: 800;">
            <span>东软云医院 HIS 系统</span>
        </el-header>
        <el-container>
            <el-aside width="200px">
                <el-row class="tac">
                    <el-col :span="12">
                        <el-menu>
                            <lable>
                                <el-submenu index="1"  id="left_nav_one">
                                <template slot="title">
                                    <span>挂号收费</span>
                                </template>
                                <el-menu-item-group>
                                    <el-menu-item index="1-1" @click="dolink">选项1</el-menu-item>
                                    <el-menu-item index="1-2">选项2</el-menu-item>
                                    <el-menu-item index="1-3">选项2</el-menu-item>
                                    <el-menu-item index="1-4">选项2</el-menu-item>
                                    <el-menu-item index="1-5">选项2</el-menu-item>
                                    <el-menu-item index="1-6">选项2</el-menu-item>
                                    <el-menu-item index="1-7">选项2</el-menu-item>
                                    <el-menu-item index="1-8">选项2</el-menu-item>
                                    <el-menu-item index="1-8">选项2</el-menu-item>
                                    <el-menu-item index="1-9">选项2</el-menu-item>
                                </el-menu-item-group>
                            </el-submenu>
                            </lable>
                            <lable>
                                <el-submenu index="2"  id="left_nav_two">
                                    <template slot="title">
                                        <span>门诊医生</span>
                                    </template>
                                    <el-menu-item-group>
                                        <el-menu-item index="1-1">选项1</el-menu-item>
                                        <el-menu-item index="1-2">选项2</el-menu-item>
                                        <el-menu-item index="1-3">选项2</el-menu-item>
                                        <el-menu-item index="1-4">选项2</el-menu-item>
                                        <el-menu-item index="1-5">选项2</el-menu-item>
                                        <el-menu-item index="1-6">选项2</el-menu-item>
                                        <el-menu-item index="1-7">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-9">选项2</el-menu-item>
                                    </el-menu-item-group>
                                </el-submenu>
                            </lable>
                            <lable>
                                <el-submenu index="3"  id="left_nav_three">
                                    <template slot="title">
                                        <span>医技处理</span>
                                    </template>
                                    <el-menu-item-group>
                                        <el-menu-item index="1-1">选项1</el-menu-item>
                                        <el-menu-item index="1-2">选项2</el-menu-item>
                                        <el-menu-item index="1-3">选项2</el-menu-item>
                                        <el-menu-item index="1-4">选项2</el-menu-item>
                                        <el-menu-item index="1-5">选项2</el-menu-item>
                                        <el-menu-item index="1-6">选项2</el-menu-item>
                                        <el-menu-item index="1-7">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-9">选项2</el-menu-item>
                                    </el-menu-item-group>
                                </el-submenu>
                            </lable>
                            <lable>
                                <el-submenu index="4"  id="left_nav_four">
                                    <template slot="title">
                                        <span>药房管理</span>
                                    </template>
                                    <el-menu-item-group>
                                        <el-menu-item index="1-1">选项1</el-menu-item>
                                        <el-menu-item index="1-2">选项2</el-menu-item>
                                        <el-menu-item index="1-3">选项2</el-menu-item>
                                        <el-menu-item index="1-4">选项2</el-menu-item>
                                        <el-menu-item index="1-5">选项2</el-menu-item>
                                        <el-menu-item index="1-6">选项2</el-menu-item>
                                        <el-menu-item index="1-7">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-9">选项2</el-menu-item>
                                    </el-menu-item-group>
                                </el-submenu>
                            </lable>
                            <lable>
                                <el-submenu index="5"  id="left_nav_five">
                                    <template slot="title">
                                        <span>财务管理</span>
                                    </template>
                                    <el-menu-item-group>
                                        <el-menu-item index="1-1">选项1</el-menu-item>
                                        <el-menu-item index="1-2">选项2</el-menu-item>
                                        <el-menu-item index="1-3">选项2</el-menu-item>
                                        <el-menu-item index="1-4">选项2</el-menu-item>
                                        <el-menu-item index="1-5">选项2</el-menu-item>
                                        <el-menu-item index="1-6">选项2</el-menu-item>
                                        <el-menu-item index="1-7">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-9">选项2</el-menu-item>
                                    </el-menu-item-group>
                                </el-submenu>
                            </lable>
                            <lable>
                                <el-submenu index="6"  id="left_nav_six">
                                    <template slot="title">
                                        <span>系统信息</span>
                                    </template>
                                    <el-menu-item-group>
                                        <el-menu-item index="1-1">选项1</el-menu-item>
                                        <el-menu-item index="1-2">选项2</el-menu-item>
                                        <el-menu-item index="1-3">选项2</el-menu-item>
                                        <el-menu-item index="1-4">选项2</el-menu-item>
                                        <el-menu-item index="1-5">选项2</el-menu-item>
                                        <el-menu-item index="1-6">选项2</el-menu-item>
                                        <el-menu-item index="1-7">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-8">选项2</el-menu-item>
                                        <el-menu-item index="1-9">选项2</el-menu-item>
                                    </el-menu-item-group>
                                </el-submenu>
                            </lable>

                        </el-menu>
                    </el-col>
                </el-row>

            </el-aside>
            <el-main>
                <router-view></router-view>
            </el-main>
        </el-container>
    </el-container>

</template>

<script>
    export default {
        name: "Home",
        methods:{
            dolink:function () {
                this.$router.push('/about')
                
            }
            
        },
    }
</script>

<style scoped>
    .el-header, .el-footer {
        background-color: #B3C0D1;
        color: #333;
        text-align: left;
        line-height: 60px;
        height: 60px;
    }

    .el-aside {
        background-color: #D3DCE6;
        color: #333;
        text-align: center;
        line-height: 200px;
        height: 500px;
    }

    .el-main {
        background-color: #E9EEF3;
        color: #333;
        text-align: center;
        line-height: 160px;
    }

    body > .el-container {
        margin-bottom: 40px;
    }

    .el-container:nth-child(5) .el-aside,
    .el-container:nth-child(6) .el-aside {
        line-height: 260px;
    }

    .el-container:nth-child(7) .el-aside {
        line-height: 320px;
    }
    #left_nav_one{
        width: 200px;
        background-color: #E9EEF3;
    }
    #left_nav_two{
        width: 200px;
        background-color: #E9EEF3;
    }
    #left_nav_three{
        width: 200px;
        background-color: #E9EEF3;
    }
    #left_nav_four{
        width: 200px;
        background-color: #E9EEF3;
    }
    #left_nav_five{
        width: 200px;
        background-color: #E9EEF3;
    }
    #left_nav_six{
        width: 200px;
        background-color: #E9EEF3;
    }

</style>