<!--
  * @Author: Fred R. Zhen
  * @Date: 2022/2/5 12:59
  * @Email: fred.zhen@gmail.com
-->
<template>
  <v-container>
    <v-row justify="center">
      <v-btn
          class="mt-16"
          color="primary"
          dark
          @click.stop="dialog = true">
        Modal Example
      </v-btn>
      <v-dialog
          v-modal="dialog"
          max-width="300">
        <v-card>
          <v-card-title class="text-h5">
            Modal Example
          </v-card-title>
          <v-card-text>
            Suns wobble on moon at captain's quarters!
          </v-card-text>
          <v-card-actions>
            <v-btn
                color="green darken-1"
                text
                @click="dialog = false">
              Close
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-dialog>
    </v-row>
  </v-container>

</template>

<script>
import Vuetify from "@/plugins/vuetify";

export default {
  name: "ModalView",
  vuetify:new Vuetify(),
  data() {
    return {
      dialog: false,
    }
  }

}
</script>

<style scoped>

</style>
