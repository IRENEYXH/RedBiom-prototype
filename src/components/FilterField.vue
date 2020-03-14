<template>
    <div style="padding:20px; width: 100%">
        <div style="margin-bottom: 15px">
            <h6>Summary Data</h6>
            <div>
                <b-button pill variant="outline-danger" size="sm">pH</b-button>
                <b-button pill variant="outline-danger" size="sm">salinity</b-button>
                <b-button pill variant="outline-danger" size="sm">location</b-button>
                <b-button pill variant="outline-danger" size="sm">taxon</b-button>
                <b-button pill variant="outline-danger" size="sm">feature</b-button>
            </div>

            <div>
            </div>

        </div>
    </div>
</template>

<script>
    // import { D3BarChart } from 'vue-d3-charts';

    export default {
        name: "FilterField",
        components: {
            // D3BarChart
        },
        data (){
            return {
            }
        }
    }
</script>

<style scoped>
    div {
    }

    button {
        margin: 2px;
    }
</style>