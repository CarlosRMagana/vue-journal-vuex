<template>
    <div class="entry-container mb-3 pointer p-2" @click="$router.push({ name: 'entry', params: { id: 10 }})">
        <!-- Title -->
        <div class="entry-title d-flex"></div>
        <span class="text-success fs-5 fw-bold">17</span>
        <span class="mx-1 fs-5">Febrero</span>
        <span class="mx-2 fw-light">2021, jueves</span>
    

        <div class="entry-description">
            Irure ullamco et minim incididunt cupidatat. Nisi nostrud eu amet velit. Fugiat cupidatat sunt nisi fugiat. Quis cupidatat velit eiusmod esse.
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