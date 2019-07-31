<template>
<div>
	<div class="perf">
	<p><img src="../assets/perf.png"/><span class="fees">STUDENT PERFORMANCE</span></p>
		<img src="../assets/performance.png" class="image"/>

	
		<div class="grapharea">
        <p><img src="../assets/analytics.png"/><span class="fees">GENERAL STATISTICS</span></p>
        <div class="threegraphs">
            <p class="text">STUDENTS</p>
            <p class="figure">50,000</p>
            <p class="report">VIEW REPORTS</p>
        </div>
        <div class="threegraphs">
            <p class="text">PARENTS</p>
            <p class="figure">15,000</p>
            <p class="report">VIEW REPORTS</p>
        </div>
        <div class="threegraphs">
            <p class="text">TEACHERS</p>
            <p class="figure">5000</p>
            <p class="report">VIEW REPORTS</p>
        </div>
        </div>
	</div>
</div>
</template>

<script>
export default {
	name :'Performance',
}
</script>

<style scoped>
.image{
	width: 700px;
}
.fees {
   margin-left: 10px;
   color: #3B3B3B;
   font-size: 10px;
   }
.perf{
	margin-left: 280px;
  }
.grapharea {
   float: right;
   margin-top: -35px;
   }
 .threegraphs {
   width: 350px;
   height: 90px;
   background: #FFFFFF;
   border: 1px solid rgba(189, 189, 189, 0.25);
   box-sizing: border-box;
   box-shadow: 0px 4.71062px 23.5531px rgba(0, 0, 0, 0.07);
   border-radius: 4.71062px;
   margin-bottom: 10px;
   margin-right: 10px;
   }
 .text {
    font-size: 10px;
    color: #BDBDBD;
    margin-left: 20px;
    margin-top: -10px;
   }
.figure {
    font-weight: 600;
    font-size: 24px;
    color: #3B3B3B;
    margin-bottom: 20px;
    margin-top: -50px;
    margin-left: 20px;
    }
.report {
    font-weight: bold;
    font-size: 10px;
    color: #1B75BB;
    margin-top: -20px;
    margin-left: 20px;
    }
</style>