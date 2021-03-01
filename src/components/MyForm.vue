<template>
    <div>
        <input type="text" placeholder="name" />
    </div>
    <div>
        <button>Submit</button>
    </div>
</template>

<script>
import { ref } from 'vue'
export default {
    setup(){
        const name = ref('')

        return {
            name,
        }
    },
}
</script>

<style>
input[type="text"]{
    padding: 5px;
}

button {
    margin-top: 20px;
}
</style>