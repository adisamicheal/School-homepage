<template>
<div>
	<div class="absent-student">
		<p><img src="../assets/man-user.png"/><span class="fees">ABSENT STUDENT</span></p>
		<div class="absent">
			<p class="text">94.6%<p/>
			<p class="text2">STUDENT ATTENDANCE</p>
			<p class="text">6</p>
			<p class="text2">Number of students absent</p>
		</div>
	</div>
	<div class="absent2">
		</div>
</div>
</template>

<script>
export default {
	name :'Absent',
}
</script>

<style>
.absent-student{
	margin-left: 295px;
}
.fees {
   margin-left: 10px;
   color: #3B3B3B;
   font-size: 10px;
   }

.absent {
   background: #FFFFFF;
	border: 1px solid rgba(189, 189, 189, 0.25);
	box-sizing: border-box;
	box-shadow: 0px 7.51481px 37.574px rgba(0, 0, 0, 0.07);
	border-radius: 7.51481px;
	width: 259px;
	height: 233px;
   }

.text {
	font-family: Khula;
	font-style: normal;
	font-weight: bold;
	font-size: 36px;
	line-height: 58px;
  }

.text2 {
	font-family: Montserrat;
	font-style: normal;
	font-weight: normal;
	font-size: 9.56193px;
	line-height: 12px;
	color: #A79FAA;
}
.absent2{
	background: #FFFFFF;
	border: 1px solid rgba(189, 189, 189, 0.25);
	box-sizing: border-box;
	box-shadow: 0px 7.51481px 37.574px rgba(0, 0, 0, 0.07);
	border-radius: 7.51481px;
	width: 700px;
	height: 233px;
	margin-left: 600px;
	margin-top: -245px;
}
</style>