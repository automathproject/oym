<script>
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
  import Katex from "./lib/Katex.svelte"
	
	// math equations
	const math = "ax^2+bx+c=0";
	const math2 = "x=-\\frac{-b\\pm\\sqrt{b^2-4ac}}{2a}";
</script>

<main>

  <h1>Open your maths</h1>
<div>
Our math equation: <Katex math={math2}/> and it is inline.
 </div>

</main>

<style>
  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }
</style>
