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
    <div class="h-100 p-5 text-bg-dark rounded-3 my_img">

        <h2>{{ jumboTitle }}</h2>
        <p>{{ jumboInfo }}</p>
        <button class="btn btn-outline-light" type="button">Button</button>


    </div>
</template>