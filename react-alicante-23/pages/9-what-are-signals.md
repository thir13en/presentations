<section>
	<h1>What are signals?</h1>
	<h3>Signals, Derivations, Reactions</h3>
	<ul>
		<li><b>Signals</b> are the basic primitive of this so called "fine-grained reactive paradigm".</li>
		<li>They consist of a getter, setter, and a value</li>
		<li>The important detail is that both the get and set can run arbitrary code.</li>
		<li>Signals alone are not very interesting without their partner in crime: <b>Reactions</b>, which observe our Signals and re-run them every time their value updates. These are wrapped function expressions that run initially, and whenever our signals update.</li>
		<li>I think on <b>Derivations</b> as composed/processed signals that are able to yield a derived value based on the value stored in the signal that they relate to.</li>
	</ul>
	<p><a href="https://dev.to/ryansolid/a-hands-on-introduction-to-fine-grained-reactivity-3ndf">Code examples</a></p>
	<p><a href="https://dev.to/this-is-learning/the-evolution-of-signals-in-javascript-8ob">Historical background and motivations</a></p>
</section>