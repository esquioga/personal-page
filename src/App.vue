<template>
  <v-app>
    <v-container>
      <v-card elevation="10" dark>
        <v-card-title> João Esquioga </v-card-title>
        <v-card-subtitle> Fullstack Developer </v-card-subtitle>
        <v-divider/>
        <v-card-text>
          <v-container grid-list-md text-xs-center>
            <v-layout row justify-center align-center>
              <v-flex xs4>
                <v-img width="240px" height="240px" src="./assets/img/avatar-placeholder.png"/>
              </v-flex>
              <v-flex xs5>
                <v-card elevation="0">
                  <v-card-title>Lorem Ipsum</v-card-title>
                  <v-card-text>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras porta neque in urna varius, ut dictum ligula pretium. Sed non orci massa. Pellentesque volutpat lorem arcu, ac egestas felis varius sit amet. Etiam pharetra ex vel nulla venenatis, eget gravida metus fringilla. Cras congue ullamcorper tempor. Ut mollis bibendum risus vitae posuere. Integer tincidunt in ligula eget ultricies. Suspendisse condimentum lobortis euismod. Duis augue tellus, volutpat eget dolor sit amet, tempus sodales elit. Vivamus id lacinia lectus, eu consequat ante.
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>          
        </v-card-text>
        <v-card-title class="section-title">What I do </v-card-title>
        <div class="custom-divider"/>
      </v-card>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
  }),
};
</script>
<style lang="scss" scoped>

.v-application {
  background-color: #F5F5F5 !important;
}

.container {
  .v-card {
    .section-title {
      padding: 0px 16px;
    }
    .custom-divider {
      width: 36px;
      margin: 0px 16px;
      padding: 0px;
      border-bottom: 1px solid #F5F5F5;
    }
  }
}

</style>
