<template>
    <div style="padding:20px; width: 100%">
        <div style="margin-bottom: 15px">
            <h8>Found 105 artifacts with 1394 samples</h8>
            <h6>Summary Data</h6>
            <div>
                <b-button pill variant="outline-danger" size="sm">pH</b-button>
                <b-button pill variant="outline-danger" size="sm">salinity</b-button>
                <b-button pill variant="outline-danger" size="sm">location</b-button>
                <b-button pill variant="outline-danger" size="sm">taxon</b-button>
                <b-button pill variant="outline-danger" size="sm">feature</b-button>
            </div>

        </div>
    </div>
</template>

<script>
    export default {
        name: "FilterField"
    }
</script>

<style scoped>
    div {
    }

    button {
        margin: 2px;
    }
</style>