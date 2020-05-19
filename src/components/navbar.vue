<template>
  <q-header bordered class="bg-white text-white">
    <q-toolbar>
      <q-btn dense flat round icon="menu" @click="left = !left" />

      <q-toolbar-title>
        <q-avatar>
          <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg" />
        </q-avatar>
        Title
      </q-toolbar-title>
    </q-toolbar>
  </q-header>
  <q-drawer v-model="left" side="left" behavior="mobile" elevated>
    <!-- drawer content -->
  </q-drawer>
</template>

<script>
export default {};
</script>

<style></style>
