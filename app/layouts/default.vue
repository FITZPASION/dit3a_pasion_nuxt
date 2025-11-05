
<template>
  <div>
    <v-app>
      <v-navigation-drawer
        expand-on-hover
        permanent
        rail
      >
        <v-list>
          <v-list-item
            prepend-avatar="https://randomuser.me/api/portraits/men/85.jpg"
            subtitle="fitzpasion"
            title="dit3a"
          ></v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list density="compact" nav>
          <v-list-item to="/" prepend-icon="mdi-robot" title="Dashboard" value="myfiles"></v-list-item>
          <v-list-item to="inventory" prepend-icon="mdi-penguin" title="Inventory" value="shared"></v-list-item>
          <v-list-item prepend-icon="mdi-cat" title="Category" value="starred"></v-list-item>
        </v-list>
      </v-navigation-drawer>

      <v-app-bar :elevation="2">
  <template v-slot:prepend>
    <v-app-bar-nav-icon></v-app-bar-nav-icon>
  </template>

  <v-app-bar-title>Application Bar</v-app-bar-title>
</v-app-bar>
    </v-app>
  </div>
</template>