<script>
  import leelaAndHerGoat from "../images/leela-and-her-goat.webp";
  import theLittleRedCar from "../images/the-little-red-car.webp";
  import kikiAndKikusAdventure from "../images/kiki-and-kikus-adventure.webp";
</script>

<h1>Shorts</h1>

<ul>
  <li>
    <a href="/leela-and-her-goat">Leela and Her Goat</a>
    <p>Leela was a little girl. She lived in a village. Leela had a pet goat. The goat was small and white...
      <a href="/leela-and-her-goat" class="image-link">
        <img src={leelaAndHerGoat} alt="Leela and Her Goat" class="story-img" />
      </a>
    </p>
  </li>
  <li>
    <a href="/the-little-red-car">The Little Red Car</a>
    <p>This is a little red car. The car is a toy. A little girl sees the car. The girl is happy...
      <a href="/the-little-red-car" class="image-link">
        <img src={theLittleRedCar} alt="The Little Red Car" class="story-img" />
      </a>
    </p>
  </li>
  <li>
    <a href="/kiki-and-kikus-adventure">Kiki and Kiku's Adventure</a>
    <p>Kiki and Kiku are brother and sister. They play under the big tree. The sun is up in the sky...
      <a href="/kiki-and-kikus-adventure" class="image-link">
        <img src={kikiAndKikusAdventure} alt="Kiki and Kiku's Adventure" class="story-img" />
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

  a:hover, a.image-link:hover {
    border-bottom: none;
  }

  a.image-link:hover img {
    filter: grayscale(20%);
  }


  p {
    font-size: 1.4em;
  }

  a {
    display: block;
    font-size: 1.4em;
    margin-bottom: 0.4em;
  }
</style>
