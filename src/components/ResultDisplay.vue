<template>
    <div>
        <div style="height: 260px">
            <b-row>
                <b-col style="background-color: #E3E1E1; height: fit-content">
                    <h4>Summary Statistics</h4>
                    <b-table striped small :items="stats"></b-table>
                </b-col>

                <b-col style="margin: 0; padding: 0">
                    <div id="wm"></div>
                </b-col>
            </b-row>
        </div>

        <div style="height: auto">
            <h3>Result Table</h3>
            <b-table striped hover :items="results" :fields="fields"></b-table>
        </div>
    </div>
</template>

<script>
    export default {
        name: "ResultDisplay",

        data() {
            return {
                // Note `isActive` is left out and will not appear in the rendered table
                fields: ['id', 'study_title', 'datasets_summary'],
                results: [
                    { isActive: true, id: 231209, study_title: 'Sponge Response to Temperature Stress', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'TACK Community Structure in Deep Atlantic', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' },
                    { isActive: true, id: 231209, study_title: 'Dickerson', datasets_summary: 'Artifacts: 24| Sample: 522' }

                ],

                stats: [
                    { sample: 1394, study: 234, seq_instrument: 5 }
                ]
            }
        }
    }
</script>

<style scoped>
</style>