<template>
  <button @click="onClick()" :style="{background: color}" class="btn" color="light">{{text}}</button>
</template>

<script>

    export default {
        name: 'Button',
        props: {
            text: {
                type: String, 
            },
            color: String,
        },
        methods: {
          onClick() {
                console.log('click');
            }
        }
    }
</script>
