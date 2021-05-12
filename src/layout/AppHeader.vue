<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="img/app/logo.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a>
                        <img src="img/app/logo.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
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
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <router-link to="/login"  class="nav-link nav-link-icon">Login</router-link>
                </li>
                <li class="nav-item">
                     <router-link to="/register" class="nav-link nav-link-icon">Register</router-link>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
