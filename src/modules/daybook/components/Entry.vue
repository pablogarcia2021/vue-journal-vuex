<template >
    <div class="mb-3 pointer p-2 entry-container"
           @click="$router.push({name: 'entry', params:{id: 1}  })" >
       <!--  tittle -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2021, Jueves</span>
        </div>
        <div class="entry-description">
            Aute pariatur consectetur aliqua id eu. Pariatur nostrud aliqua veniam non. Consectetur aliqua consectetur incididunt dolore enim sit ex dolore nostrud dolor. Incididunt laboris ut qui enim id deserunt consequat quis proident cupidatat. Ea magna mollit labore non cupidatat reprehenderit ea esse culpa sint non tempor laboris et. Lorem laboris sit officia aute eu eu non. Et amet magna occaecat irure eiusmod laboris enim velit.

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
            background-color: lighten($color: grey, $amount: 45) ;
             transition: 0.2s all ease-in;
        }
        .entry-description{
            font-size: 12px;
        }
    }
   
    
   
</style>
