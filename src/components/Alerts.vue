<template>
    <div class="container">
        <AgroAlert     title="Alert" subtitle="some subtitle" variant="danger"/>
        <AgroAlert :onClick=doSomething title="Alert" subtitle="some subtitle" btnLabel="Click me and I'll say Hi!"/>
    </div>
</template>

<style>

</style>

<script>

import {AgroAlert} from 'agrofy-ui-components'

export default {
    components: {
        'AgroAlert': AgroAlert,
    },
    methods: {
        doSomething() {
            alert('Hi!')
        }
    }
}
</script>