<template>
    <div class = "card">
        <!-- <div class="col-6 col-md-4"> -->
       <div class="card-header">
        Chart
        </div>
        <div class="card-body">
            <bar :data="data" :option="option"> </bar>
      </div>
      
      </div>
    <!-- </div> -->
    <div class = "card">
        <!-- <div class="col-6 col-md-4"> -->
       <div class="card-header">
        Chart
        </div>
        <div class="card-body">
            <Doughnut :data="data" :option="option"> </Doughnut>
      </div>
      </div>
    <!-- </div> -->
      
</template>

<script>
import bar from './bar.vue';
import Doughnut from './Doughnut.vue';


export default{
       name:'info',
       props:[
           'data',
           'option'
       ],
       components:{
           bar,
         Doughnut
       }
}
</script>