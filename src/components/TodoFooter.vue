<template>
    <div class="clearAllContainer">
        <span class="clearBtn" @click="clearTodo">Clear All</span>
    </div>
</template>

<script>
export default {
    methods: {
        clearTodo() {
            this.$emit('removeAll');
        }
    }
}
</script>

<style>
    .clearAllContainer {
        width: 8.5rem;
        height: 50px;
        line-height: 50px;
        background-color: white;
        border-radius: 5px;
        margin: 0 auto;
    }

    .clearBtn {
        color: #e20403;
        display: black;
    }
</style>
