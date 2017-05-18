<template>
    <div >
        <Menu  width="180px" mode="vertical" active-name="1">
            <Menu-group title="内容管理">
                <Menu-item name="1">
                    <Icon type="document-text"></Icon>
                    文章管理
                </Menu-item>
                <Menu-item name="2">
                    <Icon type="chatbubbles"></Icon>
                    评论管理
                </Menu-item>
            </Menu-group>
            <Menu-group title="统计分析">
                <Menu-item name="11">
                    <Icon type="heart"></Icon>
                    用户留存
                </Menu-item>
                <Menu-item name="12">
                    <Icon type="heart-broken"></Icon>
                    流失用户
                </Menu-item>
            </Menu-group>
        </Menu>
    </div>
</template>
<script>
    export default {
        data () {
            return {
                theme2: 'light'
            }
        }
    }
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
