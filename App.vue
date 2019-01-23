<template>
    <view class="container">
        <text class="text-color-primary">{{message}}</text>
    </view>
</template>
<script>
    export default {
        data: function() {
            return {
                message: "Hello World"
            };
        }
    };
</script>
<style>
    .container {
        flex: 1;
        background-color: white;
        align-items: center;
        justify-content: center;
    }
    .text-color-primary {
        color: blue;
        font-size: 30;
    }
</style>