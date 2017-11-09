<template>
  <div class="inner cover">
    <h1 class="cover-heading">About</h1>
    <b-row>
    	<b-col md="6" sm="12" class="photo"><img src="/static/images/profile.jpeg" class="face"></img></b-col>
    	<b-col md="6" sm="12"  class="my-info">
    		<p><b>Name:</b> Hojune Yoo</p>
    		<p><b>Education:</b> Brigham Young University, BS in Computer Science</p>
        <p><b>Email:</b> <a href="mailto:diogenes0803@gmail.com">diogenes0803@gmail.com</a></p>
    		<p><i>Reason and Logic are fuel that make me run.</i></p>
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