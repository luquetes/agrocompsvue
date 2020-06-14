<template>
    <div class="container">
        <AgroInput label="Test Input" :onChange=Changed :value=inputValue />
        <AgroInput :disabled=true placeholder="Disabled" />
    </div>
</template>

<style>

</style>

<script>

import {AgroInput} from 'agrofy-ui-components'

export default {
    components: {
        'AgroInput': AgroInput
    },
    data: function () {
        return {
            inputValue: ''
        }
    },
    methods: {
        Changed(e) {
            console.log('holas', e)
            this.inputValue = e.value
        }
    }
}
</script>