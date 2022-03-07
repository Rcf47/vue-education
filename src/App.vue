<template>
    <div>
        <button @click="addLike">Like</button>
        <button @click="addDislike">Dislike</button>
        <div>
            Количество лайков: <strong>{{ likes }}</strong> 
            Количество дизлайков: <strong>{{ dislikes }}</strong> 
        </div>
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