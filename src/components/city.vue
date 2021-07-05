<template>
    <div class="locations">
       <div class="place">
        <img :src="img" width="235" height="300"/>
        <h2>{{name}}</h2>
         <slot></slot>
        
      </div>
    </div>
</template>

<script>
    export default {
       name:'city',
       props:['img', 'name'] 
    }
</script>

<style lang="scss" scoped>

</style>
