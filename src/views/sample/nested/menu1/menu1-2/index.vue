<template>
    <router-view v-slot="{ Component }">
        <div style="padding: 30px;">
            <el-alert :closable="false" title="menu 1-2" type="success">
                <component :is="Component" />
            </el-alert>
        </div>
    </router-view>
</template>
