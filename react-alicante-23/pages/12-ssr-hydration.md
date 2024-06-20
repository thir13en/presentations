<h3>SSR with hidration strategy</h3>

<p>Initial HTML is generated on the server and sent to the client, where JavaScript then takes over to make the page interactive.</p>

<style>
	li.small {
		font-size: .1rem;
	}
</style>

<ul>
	<li class="small">Faster Initial Load: The HTML is fully rendered on the server, leading to quicker initial page loads and content visibility.</li>
	<li>SEO Friendly: Search engines can easily crawl and index the fully rendered HTML, improving search engine optimization.</li>
	<li>Reduced Server Load: Offloads the rendering process to the client, decreasing server resource consumption.</li>
	<li>Better Performance for Low-end Devices: Reduces the client's workload, beneficial for users with slower devices or limited processing power.</li>
</ul>

<h3>Again...</h3>
<p>We face some challenges:</p>
<ul>
	<li>Increased Server Load: The server handles the rendering, leading to higher server resource consumption and potentially increased costs.</li>
	<li>Complexity in Development: Implementing SSR with hydration can be more complex, requiring careful management of server and client code.</li>
	<li>Longer Time to Interactive: Although the initial content loads faster, the page may remain unresponsive until JavaScript is fully loaded and executed on the client side.</li>
</ul>

<img src="assets/dt-logo.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />