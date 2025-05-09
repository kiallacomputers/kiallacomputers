<template>
  <fwb-navbar>
    <template #logo>
      <fwb-navbar-logo alt="KC logo" image-url="/images/logo.png" link="/">
        Kialla Computers
      </fwb-navbar-logo>
    </template>
    <template #default="{ isShowMenu }">
      <fwb-navbar-collapse :is-show-menu="isShowMenu">
        <fwb-navbar-link is-active link="/"> Home </fwb-navbar-link>
        <fwb-navbar-link link="/store"> Store </fwb-navbar-link>
        <fwb-navbar-link link="/about"> About </fwb-navbar-link>
      </fwb-navbar-collapse>
    </template>
  </fwb-navbar>
</template>

<script setup>
import { FwbNavbar, FwbNavbarCollapse, FwbNavbarLink, FwbNavbarLogo } from 'flowbite-vue'
</script>
