<template>
    <div class="modal" v-show="value">
        <div class="container">
          <div class="modal-title">Direction</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Modal',
        props: {
                value: {
                    required: true
                }
            }
    };
</script>

<style lang="css" scoped>
    .modal {
        background-color: rgba(0, 0, 0, 0.7);
        height: 80%;
    }
</style>