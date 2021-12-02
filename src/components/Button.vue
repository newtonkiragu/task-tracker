<template>
    <button @click="onClick()" :style="{background: color}" class="btn">{{text}}</button>
</template>

<script>
//  import { MDBBtn } from "mdb-vue-ui-kit";

    export default {
        name: 'Button',
        components: {
            // MDBBtn
        },
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
