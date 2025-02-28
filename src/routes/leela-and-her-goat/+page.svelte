<script>
  import leelaAndHerGoat from "../../images/leela-and-her-goat.webp";

  function highlightNouns() {
    const nouns = document.querySelectorAll(".noun");
    nouns.forEach((noun) => {
      noun.style.background = "#2980b9";
      noun.style.color = "white";
      noun.style.padding = "0 0.2em";
    });
  }
</script>

<h1>Leela and Her Goat</h1>

<img src={leelaAndHerGoat} alt="Leela and Her Goat" class="story-img" />

<p>
  Leela was a little <span class="noun">girl</span>.<br />
  She lived in a <span class="noun">village</span>.<br />
  Leela had a pet <span class="noun">goat</span>.<br />
  The goat was small and white.<br />
</p>

<p>
  One day, the goat got stuck in the <span class="noun">mud</span>.<br />
  Leela saw her goat. "Oh no!" she said.<br />
</p>

<p>
  Leela tried to pull the goat.<br />
  But the goat did not move.<br />
  Leela was sad. Her goat was stuck.<br />
</p>

<p>
  Then, Leela's <span class="noun">friend</span>, Ravi, came by.<br />
  "What happened?" he asked.<br />
</p>

<p>
  "My goat is stuck," said Leela.<br />
  Ravi smiled. "We can help together."<br />
</p>

<p>
  Ravi and Leela pulled the goat.<br />
  The goat came out slowly. It was free!<br />
</p>

<p>
  Leela was happy. She hugged her goat.<br />
  "Thank you, Ravi!" she said.<br />
</p>

<p>
  Ravi smiled. "Friends help friends."<br />
  They played with the goat.<br />
</p>

<h2>Learning aids</h2>
<button onclick={highlightNouns}>Highlight nouns</button>

<h2>About story</h2>
<div class="mute">
  <p>Word Count: 24 sentences (approximately 100-150 words)</p>
</div>

<style>
  .story-img {
    width: 100%;
    max-width: 600px;
  }

  p {
    font-size: 1.4em;
  }

  button {
    font-size: 1.4em;
  }

  .mute {
    color: #aaa;
  }
</style>
