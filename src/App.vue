<template>
  <q-layout view="hHh lpR fFf">
    <q-header elevated>
      <q-toolbar class="custom-toolbar">

        <div class="toolbar-center">
          <q-btn-dropdown class="custom-dropdown" label="Daftar Tugas" dropdown-icon="~">
            <q-list class="nav-list">
              <q-item clickable v-close-popup>
                <router-link to="/">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Weather</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas1">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Tugas 1</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas2">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Tugas 2</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas3">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Tugas 3</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas4">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Tugas 4</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas5">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Tugas 5</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas6">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Tugas 6</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas7">
                  <q-item-section>
                    <q-item-label style="color: var(--light-beige);">Tugas 7</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
            </q-list>
          </q-btn-dropdown>
        </div>

      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view></router-view>
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  setup() {

  },
};
</script>

<style>
@import './assets/index.css';

.custom-toolbar {
  background-color: var(--dark-red);
  color: var(--light-beige);
  text-decoration: none;
  display: flex;
  justify-content: center;
  align-items: center;
}

.toolbar-center {
  display: flex;
  justify-content: center;
  width: 100%;
}

.custom-dropdown {
  background-color: var(--medium-red);
  color: var(--light-beige);
}

.nav-list {
  background-color: var(--dark-red);
  color: var(--light-beige);
}

.q-item-section {
  color: var(--beige) !important;
}
</style>
