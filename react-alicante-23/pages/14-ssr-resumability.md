<h3>SSR with resumability strategy</h3>

<p>The initial HTML is rendered on the server, and the client-side JavaScript "resumes" or continues the application state from where the server left off without re-executing the entire page logic.</p>

<ul>
	<li>Efficient Loading: Allows the application to resume with minimal JavaScript execution, providing a faster and smoother user experience.</li>
	<li>Reduced Redundancy: Avoids the need to duplicate rendering logic on the client, resulting in less code to maintain and send to the client.</li>
	<li>Improved Performance: Minimizes the JavaScript bundle size and execution time, benefiting users with slower devices or connections.</li>
</ul>

<h3>More pain...</h3>
<ul>
	<li>Complex State Management: Ensuring the server-rendered state is accurately resumed on the client can be challenging and error-prone.</li>
	<li>Limited Framework Support: Not all frameworks support resumability, potentially limiting technology choices or requiring custom solutions.</li>
	<li>Debugging Difficulties: Debugging issues that arise during the handoff from server to client can be more complex compared to traditional SSR or client-side rendering.</li>
</ul>

<img src="assets/dt-logo.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />

<style>
	li {
		font-size: 1rem;
	}
</style>