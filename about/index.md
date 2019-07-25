---
layout: none
current: about
navigation: true
logo: 'assets/images/ghost.png'
class: page-template
subclass: 'post page'
---
<meta name="description" content="{% if page.description %}{{ page.description }}{% else %}{{ site.description }}{% endif %}" />
 <link rel="shortcut icon" href="{{ site.url }}{{ site.baseurl }}{{ site.favicon }}" type="image/png" />


<div class="about_me">
	<div class="logo"><a htef="{{site.baseurl}}"> <img class="site-logo" src="{{ site.baseurl }}{{ site.logo }}" /></a></div>
	<img src="/thgus900.github.io/assets/images/sh_about.jpg">
</div>


<style>
body{
	padding:0;
	margin:0
}
.logo{
	width:100%; 
	height:64px; 
	background: #090a0b no-repeat 50%;
}
.about_me{
	width:100%;
	height:100%;
}

.about_me img{
	width:100%;
}
</style>