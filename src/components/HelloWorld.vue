<template>
  <v-container>
    <v-row class="text-center">

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Appointments
        </h2>
      </v-col>
    </v-row>
    <v-data-table
      :headers="headers"
      :items="appointments"
      class="elevation-1"
    ></v-data-table>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      headers: [
        {
          text: 'N° Appointment', value: 'appointment'
        },
        {
          text: 'Client', value: 'client'
        },
        {
          text: 'Vehicle', value: 'vehicle'
        },
        {
          text: 'Order', value: 'order'
        },
        {
          text: 'Datetime', value: 'datetime'
        },        
        {
          text: 'Direction', value: 'direction'
        },
        {
          text: 'Total', value: 'total'
        },
      ],
      appointments: [
        {
          appointment: '0012',
          client: 'Jose Perez',
          vehicle: 'Chevrolet Aveo Family PAC-6898',
          order: 'Packet Basic + wax',
          datetime: '12/03/2020 13h00',
          direction: '6 de diciembre y Portugal',
          total: '$35.12'
        },
        {
          appointment: '0013',
          client: 'Mario Cartagena',
          vehicle: 'Toyota Zonda XGE-6898',
          order: 'Packet Pro',
          datetime: '25/03/2020 09h00',
          direction: 'Shyris y Carolina',
          total: '$50.22'
        },
        {
          appointment: '0014',
          client: 'Sebastian Sanchez',
          vehicle: 'Aston Martin DB11 PAD-4856',
          order: 'Packet Premium',
          datetime: '31/04/2020 22h00',
          direction: 'Pedro Pinto y Guerrero',
          total: '$118.36'
        },
        {
          appointment: '0015',
          client: 'Ahmed Hidalgo',
          vehicle: 'Chevrolet Aveo Family PAC-6898',
          order: 'Packet Economic',
          datetime: '17/01/2020 12h00',
          direction: 'República y Solanda',
          total: '$10.00'
        },
        {
          appointment: '0016',
          client: 'Sebastian Espinoza',
          vehicle: 'Alfa Romeo 4C PAC-5966',
          order: 'Packet Premium + double',
          datetime: '22/09/2021 09h00',
          direction: 'Napo y El salvador',
          total: '$235.36'
        },
        {
          appointment: '0017',
          client: 'Anthony Aguilera',
          vehicle: 'BMW X6 DIR-5411',
          order: 'Packet Pro',
          datetime: '30/09/2021 15h00',
          direction: 'Miranda y Dolores',
          total: '$59.63'
        },
        {
          appointment: '0018',
          client: 'Ivan Rodriguez',
          vehicle: 'Alpine A110 AMS-1156',
          order: 'Packet Basic',
          datetime: '13/05/2021 13h55',
          direction: 'Colon y Rodrigo de Chavez',
          total: '$30.12'
        },
        {
          appointment: '0019',
          client: 'Omar Gualotuña',
          vehicle: 'Audi A1 SER-5487',
          order: 'Packet Economic',
          datetime: '02/12/2021 19h00',
          direction: '9 de agosto y Colon',
          total: '$15.26'
        },
        {
          appointment: '0020',
          client: 'Diego Ordoñez',
          vehicle: 'Bentley Bentayga PAU-2484',
          order: 'Packet Premium',
          datetime: '25/06/2021 22h00',
          direction: 'Irlanda y Jose Merino',
          total: '$100.00'
        },
        {
          appointment: '0021',
          client: 'Ismael Garces',
          vehicle: 'Tesla Model 3 APD-2225',
          order: 'Packet Premium',
          datetime: '09/01/2021 12h00',
          direction: '10 de octubre y Shyris',
          total: '$100.00'
        },
        {
          appointment: '0022',
          client: 'Ricardo Becerra',
          vehicle: 'Tesla Model X AWF-2448',
          order: 'Packet Premium',
          datetime: '09/01/2021 15h00',
          direction: '10 de octubre y Shyris',
          total: '$100.00'
        },
      ],      
    }),
  }
</script>
