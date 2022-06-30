<template>
    <div>
        <nav class="navbar navbar-expand-md navbar-light bg-white shadow-sm">
        <div class="container">
            <h1>Boolpress</h1>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <!-- Left Side Of Navbar -->
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item">
                        <router-link to="/">Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/about">About</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/posts">Posts</router-link>
                    </li>

                </ul>

                <!-- Right Side Of Navbar -->


            </div>
        </div>
    </nav>

        <router-view></router-view>
    </div>
</template>


<script>
    export default {
        name: 'App'
    }
</script>
