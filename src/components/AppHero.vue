<script>

export default {
    data() {
        return {
            jumboTitle: 'This is my Jumbotron',
            jumboInfo: 'This my jumbotron created in AppHero.vue file'
        }
    }
}

</script>

<template>
    <div class="jumbotron jumbotron-fluid bg-success">
        <div class="container">
            <h2 class="display-4">{{ jumboTitle }}</h2>
            <p class="lead">{{ jumboInfo }}</p>
        </div>
    </div>
</template>