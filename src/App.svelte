<svelte:head>
<title>Micaiah Wallace</title>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<script src="https://kit.fontawesome.com/be05928fac.js" crossorigin="anonymous"></script>
</svelte:head>

<script>
import marked from "marked";
</script>

<style>
a {
	color: rgb(32, 32, 32);
}
a:hover, a:visited {
	color: rgb(63, 63, 63);
}
</style>

<div class="container">
	<div class="row justify-content-sm-center">
		<div class="col-xs-12 text-center">
			<img src="img/profile.jpg" alt="micaiah wallace" class="img-thumbnail rounded-circle" />
			<h2>Micaiah Wallace</h2>
			<p class="text-muted">Software Developer</p>
			<ul class="list-unstyled">
				<li><a href="https://github.com/micaiahwallace" target="_blank"><i class="fab fa-github"></i> @micaiahwallace</a></li>
				<li><a href="https://twitter.com/micaiahwallace" target="_blank"><i class="fab fa-twitter-square"></i> @micaiahwallace</a></li>
				<li><a href="https://keybase.io/sn0" target="_blank"><i class="fab fa-keybase"></i> @sn0</a></li>
			</ul>
			<hr />
			<p class="text-left">
			{@html marked(`
**about@me** #
A software developer with a vast experience in node.js but a curiosity for anything tinker with to make something cool. I like to learn new coding langauges for fun, and develop random software to see what's possible.

**Experience**

- **node.js** - 5 years web app & api development, web scraping, desktop applications. (express, mongoose, react, electron, puppeteer, webpack)
- **aws** - 4 years web app hosting, server, network & configuration management (ec2, lambda, vpc, ecs, route53)
- **docker** - 2 years production web application deployment via custom docker images on aws ecs (docker, docker-compose)
- **linux** - 5 years server deployment, management, scripting & troubleshooting (OpenSUSE, CentOS, Ubuntu, Arch)

**Projects**

- **[Xbee Communicator](https://github.com/micaiahwallace/xbeecomm)** Desktop application for communicating over serial ports, specifically xbee
			`)}
			</p>
		</div>
	</div>
</div>
