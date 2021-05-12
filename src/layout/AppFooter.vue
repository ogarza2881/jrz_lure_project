<template>
    <footer class="footer has-cards">
        <div class="container">
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a>All Rights Reserved</a>
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <router-link to="/landing"  class="nav-link nav-link-icon">About Us</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/lures" class="nav-link nav-link-icon">Lures</router-link>
                        </li>
                        <!-- <li class="nav-item">
                            <router-link to="/register" class="nav-link nav-link-icon">Contact</router-link>
                        </li> -->
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
