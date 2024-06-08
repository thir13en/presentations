<h3>SSR with islands strategy</h3>

<p>Involves rendering specific, interactive components (islands) on the client side while the rest of the page is rendered on the server.</p>

<ul>
	<li>Optimized Performance: Combines the benefits of SSR for initial load speed with client-side interactivity for dynamic components.</li>
	<li>SEO Friendly: Search engines can easily crawl and index the fully rendered HTML, improving search engine optimization.</li>
	<li>Improved User Experience: Users see the main content quickly while interactive parts (islands) become interactive without blocking the entire page.</li>
	<li>Better Resource Management: Reduces the amount of JavaScript needed to be sent to the client, improving performance on slower devices and connections.</li>
</ul>

<h3>Once again...</h3>
<ul>
	<li>Development Complexity: Requires careful planning to determine which parts of the page should be rendered on the server and which as client-side islands.</li>
	<li>Fragmented Codebase: Maintaining a codebase that separates server-rendered content and client-rendered islands can be challenging.</li>
	<li>Initial Learning Curve: Teams may need to adopt new patterns and practices, increasing the time and effort required to implement this strategy effectively.</li>
</ul>

<img src="assets/dt-logo.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />

<style>
	li {
		font-size: 1rem;
	}
</style>