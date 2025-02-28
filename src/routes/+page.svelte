<script>
  import leelaAndHerGoat from "../images/leela-and-her-goat.webp";
</script>

<h1>Shorts</h1>

<ul>
  <li>
    <a href="/leela-and-her-goat">Leela and Her Goat</a>
    <br/>
    <p>Leela was a little girl. She lived in a village. Leela had a pet goat. The goat was small and white...
      <a href="/leela-and-her-goat" class="image-link">
        <img src={leelaAndHerGoat} alt="Leela and Her Goat" class="story-img" />
      </a>
    </p>
  </li>
</ul>

<style>
  .story-img {
      width: 100%;
      max-width: 300px;
      filter: grayscale(60%);
      transition: filter 0.5s;
  }

  a.image-link:hover {
    border-bottom: none;
  }

  a.image-link:hover img {
    filter: grayscale(20%);
  }


  p {
    font-size: 1.4em;
  }

  a {
    font-size: 1.4em;
  }
</style>
