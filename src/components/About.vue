<template>
  <div class="inner cover">
    <h1 class="cover-heading">About</h1>
    <b-row>
    	<b-col md="6" sm="12" class="photo"><img src="/static/images/profile.jpeg" class="face"></img></b-col>
    	<b-col md="6" sm="12"  class="my-info">
    		<p>Name: Hojune Yoo</p>
    		<p>Education: Brigham Young University, BS in Computer Science</p>
    		<p>Reason and Logic are fuel that make me run. For the best result, you will need to have me understand throughly before you make me to work.</p>
    	</b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style>
.cover-heading {
  margin-bottom:50px;
}
.face {
	width:200px;
	height:200px;
}
.my-info{
	text-align:left;
}
.photo {
	margin-bottom:50px;
}
</style>