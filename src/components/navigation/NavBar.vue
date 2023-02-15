<template>
  <v-app-bar color="background" height="170">
    <v-avatar style="margin-left: 10px" size="160" @click="drawer = !drawer">
      <v-img src="../../assets/arnaud-profile.jpg"></v-img>
    </v-avatar>

    <v-app-bar-title style="font-size: 30px">Arnaud MATUREL</v-app-bar-title>

    <v-card elevation="12">
      <v-card-title>4th year IT Engineer in sandwich curses</v-card-title>
    </v-card>

    <v-spacer></v-spacer>

    <v-btn @click="toggleTheme" elevation="12">
      switch theme
    </v-btn>
  </v-app-bar>

  <v-navigation-drawer v-model="drawer" color="background" floating>
    <v-list nav>
      <v-list-item prepend-icon="mdi-cog-outline" title="Skills" value="skills" style="font-size: 20px"></v-list-item>
      <v-list-item prepend-icon="mdi-school-outline" title="Studies" value="studies" style="font-size: 20px"></v-list-item>
      <v-list-item prepend-icon="mdi-professional-hexagon" title="Professional" value="professional" style="font-size: 20px"></v-list-item>
      <v-list-item prepend-icon="mdi-ticket" title="Hobbies" value="hobbies" style="font-size: 20px"></v-list-item>
      <v-list-item prepend-icon="mdi-code-array" title="Realisations" value="realisations" style="font-size: 20px"></v-list-item>
    </v-list>
  </v-navigation-drawer>
</template>

<script>
import { useTheme } from "vuetify";

export default {
  name: "NavBar",
  data () {
    return {
      drawer: true
    }
  },
  setup () {
    const theme = useTheme()

    return {
      theme,
      toggleTheme: () => theme.global.name.value = theme.global.current.value.dark ? 'light' : 'dark'
    }
  }
}
</script>

<style scoped>

</style>