<h3>SSR with resumability strategy</h3>

<p>The initial HTML is rendered on the server Javascript is microbundled and sent only when needed</p>

<h4>Pros</h4>
<ul>
	<li>Efficient Loading: provide javascript on demand</li>
	<li>Reduced Redundancy: Avoids the need to duplicate rendering logic on the client</li>
	<li>Improved Performance: Minimizes the JavaScript bundle size and execution time</li>
</ul>

<h4>Cons</h4>
<ul>
	<li>Complex State Management: we now have state spread among server and client</li>
	<li>Limited Framework Support: qwik is the main contender for now</li>
	<li>Debugging Difficulties: what can go wrong?</li>
</ul>

<img src="assets/dt-logo.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />