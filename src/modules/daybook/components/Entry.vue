<template>
    <div 
        class="entry-container mb-3 pointer p-2"
        @click="$router.push({ name: 'entry', params: { id: 10} })"
    >
    <!-- Titulo-->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Marzo</span>
            <span class="mx-2 fw-light">2022</span>
        </div>

    <div class="entry-description">
       Est non laboris cupidatat et duis duis dolor culpa velit dolore exercitation tempor eu. Aute ea elit reprehenderit ad. Mollit ipsum do labore laboris Lorem laborum ad exercitation sit. Aliqua anim minim ullamco quis duis elit Lorem do aliquip. Consequat sint in ex officia aliquip laboris exercitation eiusmod esse. Aute velit aliqua eiusmod sint nostrud. Aute quis consequat in velit culpa ipsum ea incididunt adipisicing.
    </div>

    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    .entry-description{
        font-size: 12px;
    }
}

</style>