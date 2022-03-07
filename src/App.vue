<template>
    <div>
        
    </div>
</template>

<script>
    export default {
        data() {
            return {
                likes: -1,
                dislikes: 0,
            }
        },
        methods: {
            addLike() {
                this.likes += 1;
            },

            addDislike() {
                this.dislikes += 1;
            }
        },
    }
</script>

<style lang="">
    
</style>