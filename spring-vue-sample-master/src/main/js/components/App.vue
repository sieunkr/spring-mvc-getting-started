<template>
    <div class="row">
        <div class="col-md-4">
            Menu
            <router-link to="/">Home1</router-link>
            <router-link to="/product/">Products</router-link>
        </div>
        <div class="col-md-6">
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
    import "bootstrap/dist/css/bootstrap.min.css";

    export default {
    };
</script>
