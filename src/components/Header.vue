<template>
    <div>
        <b-navbar toggleable="lg" type="dark" style="background-color: #842929">
            <b-navbar-brand href="#">RedBiom</b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <b-nav-item href="https://qiita.ucsd.edu/" target="_blank">Qiita</b-nav-item>
                    <b-nav-item href="https://qiita.ucsd.edu/static/doc/html/redbiom.html" target="_blank">Tutorial</b-nav-item>
                    <b-nav-item href="https://github.com/biocore/qiita" target="_blank">GitHub</b-nav-item>
                </b-navbar-nav>

                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto" style="margin-right: 40px">
                    <h6 style="color: #FCFCFC">Log in to access full functionality</h6>
                    <b-button size="sm" variant="light" type="submit">Login</b-button>
                    <b-button size="sm" variant="outline-light" type="submit">Sign up</b-button>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    button{
        margin-left: 10px;
    }
</style>