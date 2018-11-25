<template lang="pug">
    div
        div(:class="$style.test") test

</template>

<script>
export default {
    name: 'pugStylusCssModuleDemo',
    data () {
        return {}
    }
}
</script>

<style lang="stylus" module>
.test
    color blue
</style>
