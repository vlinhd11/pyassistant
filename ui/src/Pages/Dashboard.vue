<template>
  <v-container grid-list-md class="mt-1">
    <v-layout row wrap>
      <v-flex md7>
        <v-card class="card ma-1">
            <v-card-title primary-title>
              <div class="headline">Unlimited music now</div>
              <div>Listen to your favorite artists and albums whenever and wherever, online and offline.</div>
            </v-card-title>
            <v-card-actions>
              <v-btn flat>Listen now</v-btn>
            </v-card-actions>
          </v-card>
      </v-flex>
      <v-flex md5>
        <v-card class="card ma-1">
            <v-card-title primary-title>
              <div class="headline">Unlimited music now</div>
              <div>Listen to your favorite artists and albums whenever and wherever, online and offline.</div>
            </v-card-title>
            <v-card-actions>
              <v-btn flat>Listen now</v-btn>
            </v-card-actions>
          </v-card>
      </v-flex>

    </v-layout>
    <v-layout row wrap>
      <v-flex md5>
        <v-card class="card ma-1">
            <v-card-title primary-title>
              <div class="headline">Unlimited music now</div>
              <div>Listen to your favorite artists and albums whenever and wherever, online and offline.</div>
            </v-card-title>
            <v-card-actions>
              <v-btn flat>Listen now</v-btn>
            </v-card-actions>
          </v-card>
      </v-flex>
      <v-flex md7>
        <v-card class="card ma-1">
            <v-card-title primary-title>
              <div class="headline">Unlimited music now</div>
              <div>Listen to your favorite artists and albums whenever and wherever, online and offline.</div>
            </v-card-title>
            <v-card-actions>
              <v-btn flat>Listen now</v-btn>
            </v-card-actions>
          </v-card>
      </v-flex>

    </v-layout>

  </v-container>

</template>

<script>

  export default {
    name: 'app',
    data () {
      return {
        setting:{

        }
      }
    },
    watch: {

    },
    mounted: function () {
      let inst = this;
      this.$ws.addEventListener('open', function () {

      });

      this.$ws.addEventListener('message', function (msg) {
        let data = JSON.parse(msg.data);


      });


    },
    destroyed: function () {

    },
    methods: {

    },
    watch: {

    }
  }
</script>

<style>

</style>
