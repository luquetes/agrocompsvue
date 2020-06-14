<template>
    <div class="container">
      <AgroButton label="test" />
      <AgroButton label="test" variant="outlineSecondary"/>
      <AgroButton label="test" variant="outlinePrimary"/>
      <AgroButton label="test" size="sm" />
      <AgroButton label="test" size="md" />
      <AgroButton label="test" size="lg" />
      <AgroButton label="test" size="xl" />
      <AgroButton label="test" :disabled="true" />
      <AgroButton label="test" :loading="true" />
      <AgroButton label="testbutton" :onClick=saludar />
      <AgroButton label="test" iname="arrow-right" />
      <AgroButton label="test" iname="arrow-right" iposition="left" />
      <AgroButton label="custom Class" className="sarasa" />
    </div>
</template>

<style>

</style>

<script>

import {AgroButton} from 'agrofy-ui-components'

export default {
    components: {
        'AgroButton': AgroButton
    },
    methods: {
        saludar() {
        alert('holas')
        }
    }
}
</script>

<style scoped>
    >>> .sarasa {
        background: red;
    }

    >>> .sarasa:hover {
        background: blue;
    }
</style>