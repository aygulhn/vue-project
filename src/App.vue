<template>
  <div>
    <app-counter/>
    <app-car/>
  </div>
</template>

<script>
    import Car from './Car'
    import Counter from './Counter'

    export default {
        components: {
            appCar: Car,
            appCounter: Counter
        }
    }
</script>

<style>

</style>
