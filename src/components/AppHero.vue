<template>
    <section>
        <div class="w-50">
            <h2 class="text-uppercase fw-bold">{{ title }}</h2>
            <p>{{ paragraph }}</p>
            <div>
                <button class="btn btn-light me-3">Download for Windows</button>
                <button class="btn btn-dark">Open Discord in browser</button>
            </div>
        </div>
        
    </section>
</template>

<script>
    export default {
        name: 'AppHero',
        data(){
            return{
                title: 'imagine a place...',
                paragraph: '...where you can belong to a school club, a gaming group, or a worldwide art community. Where just you and a handful of friends can spend time together. A place that makes it easy to talk every day and hang out more often.',

            }
        }
    }
</script>

<style lang="scss" scoped>

</style>