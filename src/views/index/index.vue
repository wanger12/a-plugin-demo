<template>
    <div>
        <a-button>
            <router-link class="navbar-brand" to="print">print打印</router-link>
        </a-button>
        <a-button>
            <router-link class="navbar-brand" to="table-excel">table-excel导出</router-link>
        </a-button>   
        <a-button>
            <router-link class="navbar-brand" to="file-preview">文件预览</router-link>
        </a-button>    
        <a-button>
            <router-link class="navbar-brand" to="file-preview">高德地图</router-link>
        </a-button>    
        <router-view></router-view>    
    </div>  
</template>

<script>

export default {

}
</script>

<style>

</style>