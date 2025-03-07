<script>
  import leelaAndHerGoat from "../../images/leela-and-her-goat.webp";
  import theLittleRedCar from "../../images/the-little-red-car.webp";

  function highlightNouns() {
    const nouns = document.querySelectorAll(".noun");
    nouns.forEach((noun) => {
      noun.style.background = "#2980b9";
      noun.style.color = "white";
      noun.style.padding = "0 0.2em";
    });
  }
</script>

<h1>The Little Red Car</h1>

<img src={theLittleRedCar} alt="The Little Red Car" class="story-img" />

<p>
  This is a little red car.<br />
  The car is a <span class="noun">toy</span>.<br />
</p>

<p>
  A little girl sees the <span class="noun">car</span>.<br />
  The girl is happy.<br />
</p>

<p>
  The girl plays with the car.<br />
  The car goes fast.<br />
</p>

<p>
  The car runs on the <span class="noun">floor</span>.<br />
  The girl smiles.<br />
</p>

<p>
  The girl puts the car in a <span class="noun">box</span>.<br />
  The box is near the <span class="noun">bed</span>.<br />
</p>

<p>
  The girl goes to sleep.<br />
  He dreams of the little red car.<br />
</p>

<p>
  The car is fun.<br />
  The girl is happy.<br />
</p>

<h2>Learning aids</h2>
<button onclick={highlightNouns}>Highlight nouns</button>

<h2>About story</h2>
<div class="mute">
  <p>Word Count: 14 sentences (approximately 70-80 words)</p>
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
