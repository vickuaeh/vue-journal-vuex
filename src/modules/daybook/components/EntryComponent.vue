<template>
    <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({name:'entry', params:{id:10}})"
    >
        
        <!-- titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2021, Jueves</span>            
        </div>  

        <div class="entry-description">
           Occaecat Lorem ea minim ullamco irure nisi elit ipsum. Labore commodo nulla tempor ut voluptate do proident consectetur velit. Laborum cillum excepteur ad pariatur. Excepteur id voluptate pariatur et occaecat. Sint anim sint officia sunt quis ad esse consequat proident aute enim dolor adipisicing. 
        </div>

    </div>  
</template>

<script >
</script>

<style lang="scss">
.entry-container{
    border-bottom: 1px solid #2c3e50 ;
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