<h3>Client side rendering with SPAs</h3>

<style>
	li {
		font-size: 1rem;
	}
</style>

<ul>
	<li>You dont have to go back to the server for more request, page does not refresh. You are fed your 🍝 javscript right in the browser on first load and manage application lifetime from there.</li>
	<li>Can cache core html/js bundles in a CDN</li>
	<li>Reduced Server Load: Offloads the rendering process to the client, decreasing server resource consumption.</li>
	<li>Naturally much more interactive experience</li>
</ul>

<h3>But...</h3>
<p>We face some challenges:</p>
<ul>
	<li>how our app renders on a low end device from a user doing a bus commute to work</li>
	<li>SEO gone to trash</li>
	<li>Unfriendly towards users with JS disabled</li>
</ul>

<img src="assets/dt-logo.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />