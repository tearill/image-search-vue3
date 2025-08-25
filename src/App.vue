<template>
    <div class="page-wrapper">
        <div class="content"></div>
        <footer>
            <a href=""></a>
        </footer>
    </div>
</template>

<script setup lang="ts">
import { ref, reactive } from 'vue';

const websiteInfo = reactive([
    {
        text: '使用百度前必读',
        url: 'https://www.baidu.com/duty/',
    },
    {
        text: '图片侵权投诉指引',
        url: 'https://ufo.baidu.com/listen/myhistory?type=commonQA&product_line=20103&appid=215671#?qid=11',
    },
    {
        text: '帮助中心',
        url: 'https://help.baidu.com/question?prod_en=image',
    },
    {
        text: '企业推广',
        url: 'https://e.baidu.com/lp/tongyong2/?refer=1291',
    },
    {
        text: '©2025 Baidu',
    },
    {
        text: '(京)-经营性-2017-0020',
    },
    {
        text: '京公网安备11000002000001号',
        url: 'https://beian.mps.gov.cn/#/query/webSearch?code=11000002000001',
    },
    {
        text: '京ICP证030173号',
    },
]);
</script>

<style scoped></style>
