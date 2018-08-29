<template>
    <div>
        <navbar active="page2"></navbar>
        <div class="page d-flex flex-column justify-content-center align-items-center">
            <h1>Page 2</h1>
            <p class="mb-0">{{ text }}</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Page2",
        data() {
            return {
                text: 'This is another page'
            };
        },
        mounted(){

        },
        beforeDestroy(){

        },
        methods: {

        }
    };
</script>

<style scoped>
    .page {
        min-height: calc(100vh - 98px);
        margin-top: 98px;
    }
    h1 {
        font-weight: 300;
        font-size: 2.4rem;
        user-select: none;
        cursor: default;
    }
</style>