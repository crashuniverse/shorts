<script>
  import kikiAndKikusAdventure from "../../images/kiki-and-kikus-adventure.webp";

  function highlightNouns() {
    const nouns = document.querySelectorAll(".noun");
    nouns.forEach((noun) => {
      noun.style.background = "#2980b9";
      noun.style.color = "white";
      noun.style.padding = "0 0.2em";
    });
  }
</script>

<h1>Kiki and Kiku's Adventure</h1>

<img src={kikiAndKikusAdventure} alt="Kiki and Kiku's Adventure" class="story-img" />

<p>
  Kiki and Kiku are brother and sister.<br />
  They play under the big <span class="noun">tree</span>.<br />
</p>

<p>
  The sun is up in the <span class="noun">sky</span>.<br />
  The sky is blue and bright.<br />
</p>

<p>
  Kiki sees a red flower.<br />
  Kiku sees a yellow flower.<br />
</p>

<p>
  A little bird sits on the tree.<br />
  The bird sings a happy <span class="noun">song</span>.<br />
</p>

<p>
  Kiki and Kiku run to the <span class="noun">water</span>.<br />
  They jump and play.<br />
</p>

<p>
  Kiki smiles.<br />
  Kiku smiles.<br />
</p>

<p>
  They are happy.<br />
  They have fun.<br />
</p>

<p>
  The sun goes down in the sky.<br />
  It is a happy <span class="noun">day</span>.<br />
</p>

<h2>Learning aids</h2>
<button onclick={highlightNouns}>Highlight nouns</button>

<h2>About story</h2>
<div class="mute">
  <p>Word Count: 16 sentences (approximately 80-90 words)</p>
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
