<template>
    <div class="container">
        <AgroCheckbox>Te quiero como amigo</AgroCheckbox>
        <AgroCheckbox>Deberíamos ver a otras personas</AgroCheckbox>
        <AgroCheckbox>No me dejan mis papás</AgroCheckbox>
        <AgroCheckbox :checked=true>Mi amor es el mar</AgroCheckbox>
        <AgroCheckbox :disabled=true>No quiero matarte pero si me obligas</AgroCheckbox>
    </div>
</template>

<style>

</style>

<script>

import {AgroCheckbox} from 'agrofy-ui-components'

export default {
    components: {
        'AgroCheckbox': AgroCheckbox
    },
    methods: {
        setThisChecked(e) {
            console.log(e)
        }
    }
}
</script>