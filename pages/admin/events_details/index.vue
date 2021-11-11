<template>
  <div>
    <adminNav />
    <div class="container">
      <h4>Event details</h4>
      <div class="flex-mass">
        <div class="bg1 py-1 px-3">
          <h6>Mass1</h6>
          <p>Attendes: 20/200</p>
        </div>
        <div class="bg1 py-1 px-3">
          <h6>Mass2</h6>
          <p>Attendes: 20/200</p>
        </div>
        <div class="bg1 py-1 px-3">
          <h6>Mass3</h6>
          <p>Attendes: 20/200</p>
        </div>
      </div>
      <v-btn class="right-0 bg-primary text-light py-1 px-4">Refresh</v-btn>

      <div class="py-3">
        <b-table responsive :items="items"></b-table>
    </div>


    </div>
  </div>
</template>


<script>
  export default {
    data() {
      return {
        items: [
          {
            No: '1',
            Name: 'Good Christian',
            Phone_Number: '078xxxxxxx',
            Email: 'xx@gmail.com',
            Country: 'Rwanda',
            Mass: '2',
            Registration_Date : '11/11/2020',
            // heading8: 'table cell',
            // heading9: 'table cell',
            // heading10: 'table cell',
            // heading11: 'table cell',
            // heading12: 'table cell'
          },
          {
            No: '1',
            Name: 'Good Christian',
            Phone_Number: '078xxxxxxx',
            Email: 'xx@gmail.com',
            Country: 'Rwanda',
            Mass: '2',
            Registration_Date : '11/11/2020',
            heading8: 'table cell',
            heading9: 'table cell',
            heading10: 'table cell',
            heading11: 'table cell',
            heading12: 'table cell'
          },
          {
            No: '1',
            Name: 'Good Christian',
            Phone_Number: '078xxxxxxx',
            Email: 'xx@gmail.com',
            Country: 'Rwanda',
            Mass: '2',
            Registration_Date : '11/11/2020',
            heading8: 'table cell',
            heading9: 'table cell',
            heading10: 'table cell',
            heading11: 'table cell',
            heading12: 'table cell'
          },
          {
            No: '1',
            Name: 'Good Christian',
            Phone_Number: '078xxxxxxx',
            Email: 'xx@gmail.com',
            Country: 'Rwanda',
            Mass: '2',
            Registration_Date : '11/11/2020',
            heading8: 'table cell',
            heading9: 'table cell',
            heading10: 'table cell',
            heading11: 'table cell',
            heading12: 'table cell'
          },
          {
            No: '1',
            Name: 'Good Christian',
            Phone_Number: '078xxxxxxx',
            Email: 'xx@gmail.com',
            Country: 'Rwanda',
            Mass: '2',
            Registration_Date : '11/11/2020',
            heading8: 'table cell',
            heading9: 'table cell',
            heading10: 'table cell',
            heading11: 'table cell',
            heading12: 'table cell'
          },
        ]
      }
    }
  }
</script>


<style scoped>
.container {
  padding-top: 100px;
}
.flex-mass {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.bg1 {
  background: #9c9ea326;
  border-radius: 10px;
  margin-bottom: 20px;
}
.right-0 {
  margin-left: 85%;
  margin-bottom: 30px;
  border-radius: 5px;
  cursor: pointer;
}
</style>
