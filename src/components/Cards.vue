<template>
    <div class="container">
        <AgroCard src="https://deadhomersociety.files.wordpress.com/2010/08/10.jpg" alt="Homero picado por una abeja" href="https://www.youtube.com/watch?v=U_97HcEDk2g" className="homerocard">
            <blockquote>
                La abeja me picó atrás, miren cómo me dejó!
            </blockquote>
        </AgroCard>
    </div>
</template>

<style>

    .homerocard {
        border: 1px solid yellow;
    }

</style>

<script>

import {AgroCard} from 'agrofy-ui-components'

export default {
    components: {
        'AgroCard': AgroCard
    }
}
</script>