<template>
    <section>
        <b-tabs position="is-centered">
            <b-tab-item label="Singolo anno">
                <SingleYearSeach></SingleYearSeach>
            </b-tab-item>
            <b-tab-item label="Multi anno">
                <MultiYearSearch></MultiYearSearch>
            </b-tab-item>
        </b-tabs>
    </section>
</template>

<script>
import SingleYearSeach from './SingleYearSearch.vue'
import MultiYearSearch from './MultiYearSearch.vue'

export default {
    name: 'GlobalView',
    props: {
        msg: String
    },
    components: {
        SingleYearSeach,
        MultiYearSearch
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.section-1rem-pad {
    padding: 1rem
}

</style>
