<template>
  <v-app>
    <v-main>
      <v-container fluid>
        <v-row class="yellow" justify="center" align="center">
          <v-col cols="12" md="2" class="purple lighten-4">
            <span>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis possimus id exercitationem velit dignissimos repellendus qui, neque illo! Perspiciatis id praesentium
              impedit rerum vel velit. Ipsam fugit dignissimos voluptatibus sapiente!
            </span>
          </v-col>
          <v-col cols="12" md="2" class="green lighten-5">
            <span>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis possimus id exercitationem velit dignissimos repellendus qui, neque illo!
            </span>
          </v-col>
          <v-col cols="12" md="2" class="red lighten-5" align-self="end">
            <span>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis possimus id exercitationem velit dignissimos repellendus qui, neque illo!
            </span>
          </v-col>
          <v-col cols="12" md="2" class="blue lighten-5">
            <span>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis possimus id exercitationem velit dignissimos repellendus qui, neque illo! Perspiciatis id praesentium
              impedit rerum vel velit. Ipsam fugit dignissimos voluptatibus sapiente!
            </span>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    items: [
      {
        image: 'images/cars/car1.png',
        owner: 'Robert Baumgartner',
        km: 12232,
        description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor',
      },
      {
        image: 'images/cars/car2.png',
        owner: 'Du',
        km: 12232,
        description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor',
      },
      {
        image: 'images/cars/car3.png',
        owner: 'Robert Baumgartner',
        km: 12232,
        description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor',
      },
      {
        image: 'images/cars/car4.png',
        owner: 'Dein Bruder',
        km: 12232,
        description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor',
      },
      {
        image: 'images/cars/car5.png',
        owner: 'Robert Baumgartner',
        km: 12232,
        description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor',
      },
    ],
  }),
};
</script>
