<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>My Blog</title>

  
    <style>
      body {
        background-color: #fff;
        color: #050505;
        margin: 0;
        font: 1.5em / 1.2 Arial, Helvetica, sans-serif;

      }

      img {
        max-width: 100%;
        display: block;
      }

      .logo {
        font-size: 200%;
        padding: 50px 20px;
        margin: 0 auto;
        max-width: 980px;
      }

      .grid {
        margin: 0 auto;
        padding: 0 20px;
        max-width: 980px;
        display:flex;
        gap:25px;
      }

      nav {
        background-color: #14151394;
        padding: 0.5em;
        position:sticky;
        top:0;
        z-index: 100;
      }

      nav ul {
        margin: 0;
        padding: 0;
        list-style: none;
        display:flex;
        justify-content:space-between;
        
      }

      nav a {
        color: #fffdfd;
        text-decoration: none;
        padding: 0.5em 1em;
        cursor: pointer;
      }

      .photos {
        list-style: none;
        margin: 0;
        padding: 0;
        display:grid;
        gap:1px;
        justify-content:space-between;
        grid-template-columns: auto auto;
      }
      .button:hover{
        background-color: #ffffff; 
        color: black;
      }

      .feature {
        width: 200px;
        float: left;
        margin-right: 20px;
        margin-bottom: 20px;
      }
    </style>
  </head>

  <body>
    <div class="logo">Welcome to my Blog!</div>

    <nav>
      <ul>
        <li>
          <a class="button" href="">Home</a>
        </li>
        <li>
          <a class="button" href="">Blog</a>
        </li>
        <li>
          <a class="button" href="">Travel</a>
        </li>
        <li>
          <a class="button" href="">Experience</a>
        </li>
        <li>
          <a class="button" href="">Let's connect!</a>
        </li>
      </ul>
    </nav>

    <main class="grid">
      <article>
        <h1>Assalamualaukum wbt!</h1>
        <img src="https://nordicwallart.com/cdn/shop/products/GoodVibesOnlySimpleMinimalistQuotesWallArtBlackWhiteFineArtCanvasPrintsInspirationalQuotationsPosters1.jpg?v=1593723307" alt="placeholder" class="feature" />
        <p>
          The question "What is life?" is a fundamental and philosophical one that has been pondered by scientists, 
          philosophers, and thinkers for centuries. It doesn't have a single, universally agreed-upon definition, 
          as it can be approached from various perspectives. Here are a few different ways to consider the concept of life:
        </p>
        <p>
          <b>Biological Perspective: </b>From a biological standpoint, life can be defined as a characteristic that
           distinguishes organisms from non-living things. Some key characteristics of life include the ability to grow, 
           reproduce, respond to stimuli, adapt to the environment, and maintain homeostasis (a stable internal environment). 
           Life, in this sense, is often associated with the presence of cells, which are the basic structural and functional units of living organisms.
        </p>
        <p>
         <b> Philosophical Perspective:</b> Philosophers have debated the nature of life for centuries.
          Some philosophical perspectives on life emphasize consciousness, self-awareness, and the capacity for
           thought and experience as essential aspects of being alive. Existentialist philosophers like Jean-Paul
            Sartre and Albert Camus have explored questions related to the meaning and purpose of life.
        </p>

        <p>
          <b>Chemical Perspective: </b>Life can also be examined from a chemical perspective, considering the complex biochemical 
          processes that occur within living organisms.DNA, for example, is a molecule that carries genetic information and plays
           a central role in the continuity and variation of life forms
        </p>
        <p>
          Evolutionary Perspective: The theory of evolution by natural selection, proposed by Charles Darwin, 
          provides a framework for understanding the diversity and development of life on Earth. From an evolutionary perspective, 
          life is characterized by the ability of species to change and adapt over time in response to environmental pressures.

          </p>
          <p>
          Spiritual and Cultural Perspectives: Many religions and cultures have their own beliefs and interpretations of what 
          life is and its significance. These perspectives often include ideas about the soul, the afterlife, and the moral and ethical implications of life.
        </p>
      </article>

      <aside>
        <h2>Life</h2>
        <ul class="photos">
          <li>
            <img src="https://hips.hearstapps.com/hmg-prod/images/life-quotes-zhuangzi-1665420803.png" alt="placeholder" />
          </li>
          <li>
            <img src="https://hips.hearstapps.com/hmg-prod/images/positive-life-quotes-aurelius-1582061547.jpg" alt="placeholder" />
          </li>
          <li>
            <img src="https://i.pinimg.com/736x/a5/ab/7d/a5ab7d110b4a759530a8bad1b9ea5949.jpg" alt="placeholder" />
          </li>
          <li>
            <img src="https://i.pinimg.com/1200x/71/29/7e/71297e0f961b18bc7b12d1d7a118bc43.jpg" alt="placeholder" />
          </li>
          <li>
            <img src="https://i.pinimg.com/736x/8a/a5/88/8aa588abc0f6c90c139a0f18ae8f3841.jpg" alt="placeholder" />
          </li>
        </ul>
      </aside>
    </main>
  </body>
</html>
