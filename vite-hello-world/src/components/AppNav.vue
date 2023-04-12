<template>
    <nav class="nav-style text-center p-3">
        <div class="container d-flex justify-content-between">
            <div class="logo-container">
                <img src="../assets/logo.svg" alt="">
            </div>
            <div class="list-container">
                <ul class="list-unstyled d-flex">
                    <li class="nav-item me-5">
                        <a href="#" class="nav-link">Download</a>
                    </li>
                    <li class="nav-item me-5">
                        <a href="#" class="nav-link">Nitro</a>
                    </li>
                    <li class="nav-item me-5">
                        <a href="#" class="nav-link">Discover</a>
                    </li>
                    <li class="nav-item me-5">
                        <a href="#" class="nav-link">Safety</a>
                    </li>
                    <li class="nav-item me-5">
                        <a href="#" class="nav-link">Support</a>
                    </li>
                    <li class="nav-item me-5">
                        <a href="#" class="nav-link">Blog</a>
                    </li>
                    <li class="nav-item me-5">
                        <a href="#" class="nav-link">Careers</a>
                    </li>
                </ul>
            </div>
            <div class="button-container">
                <button class="btn btn-light">Login</button>
            </div>
        </div>
        
    </nav>
</template>

<script>
    export default {
        name: 'AppNav',
        data(){
            return{
                title: 'Hello World from Vite!'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>