<template>
    <nav class="navbar navbar-expand-lg bg-dark navbar-dark py-2 fixed-top">
        <div class="container">
          <a href="#" class="navbar-brand">Bootstrap Project</a>

        <NavbarButton />
        <NavbarList />
        </div>
    </nav>
</template>

<script>
import NavbarButton from '@/components/NavbarButton.vue'
import NavbarList from '@/components/NavbarList.vue'



export default {
    name: 'TheNavbar',
    components: {
        NavbarButton,
        NavbarList
    }
}
</script>