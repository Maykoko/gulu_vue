<template>
 <div>
    <button class="g-button">hi</button>
 </div>
</template>

<script>
export default {
 props: {

 },
 data() {
 return {

 };
 },
 computed: {

 },
 created() {

 },
 mounted() {

 },
 watch: {

 },
 methods: {

 },
 components: {

 },
};
</script>

<style lang='sass'>
    .g-button{
        font-size: var(--font-size);
        height: var(--button-height);
        /* 按钮的宽度 不加是比较好的 */
        padding: 0 1em; 
        font:inherit;
        border-radius: var(--border-radius);
        border:1px solid var(--border-color);
        background:var(--button-bg)
    }
    .g-button:hover{
        border-color:var(--border-color-hover)
    }
    .g-button:active{
        background-color: var(--button-active-bg)
    }
    .g-button:focus{
        outline: none;
        /* 去掉点击蓝色边框 */
    }
</style>
