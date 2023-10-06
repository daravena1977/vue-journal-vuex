<template>
    <div 
        class="entry-container mb-3 pointer p-2"
        @click="$router.push({ name: 'entry', params: {id: 10}})"
    >

        <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">5</span>
            <span class="mx-1 fs-5">Octubre</span>
            <span class="mx-1 fw-ligth">2023, jueves</span>
        </div>

        <div class="entry-description">
            Magna culpa reprehenderit nulla aute labore amet tempor exercitation labore officia ipsum nostrud reprehenderit non. Consequat magna tempor laborum duis esse culpa. Elit nisi anim eu voluptate anim ipsum et. Reprehenderit reprehenderit fugiat cupidatat ut sint tempor.
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    
    .entry-description {
        font-size: 12px;
    }
}

</style>