<template>
    <div class="container">
        <AgroAccordion>
            <AgroAccordionItem label="Accordion Test">Hooola</AgroAccordionItem>
            <AgroAccordionItem label="Accordion Test">Hooola</AgroAccordionItem>
        </AgroAccordion>
    </div>
</template>

<style>

</style>

<script>

import {AgroAccordion, AgroAccordionItem} from 'agrofy-ui-components'

export default {
    components: {
        'AgroAccordion': AgroAccordion,
        'AgroAccordionItem' : AgroAccordionItem
    }
}
</script>