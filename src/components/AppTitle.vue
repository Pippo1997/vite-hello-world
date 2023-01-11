<script>
export default {
    name:`AppTitle`,
    data(){
        return{
            hello:`La mia prima app con vue`
        }
    }   
}
</script>

<template>
    <div>
        <h1 class="text-red">
            {{hello}}
        </h1>
    </div>
</template>

<style>
.text-red{ 
    color: red;
}
</style>