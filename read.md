- ### Description list
      <dl>
        <dt>soliloquy</dt>
        <dd>
          In drama, where a character speaks to themselves, representing their inner
          thoughts or feelings and in the process relaying them to the audience (but
          not to other characters.)
        </dd>
        <dt>monologue</dt>
        <dd>
          In drama, where a character speaks their thoughts out loud to share them
          with the audience and any other characters present.
        </dd>
        <dt>aside</dt>
        <dd>
          In drama, where a character shares a comment only with the audience for
          humorous or dramatic effect. This is usually a feeling, thought, or piece of
          additional background information.
        </dd>
      </dl>

- ### [Document and website structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

- ### [Markup validatior checker](https://validator.w3.org/)
- online shareable editor such as CodePen, jsFiddle, or Glitch.

- ### Figure
    <figure>
        <img src="/media/cc0-images/elephant-660-480.jpg"
             alt="Elephant at sunset">
        <figcaption>An elephant at sunset</figcaption>
    </figure>

- ### Article
      <article>
          <h6>Introduction to HTML</h6>
          <p>HTML is a markup language that is used for creating web pages.</p>
      </article>

- ### Aside 
      <aside>
          <h6>Apollo 13 Facts</h6>
          <p>Apollo 13 was the seventh manned mission in the American Apollo space program and the third intended to land on the Moon.</p>
      </aside>

- ### Audio
  <audio controls="controls" src="birds.mp3">
      Your browser does not support the HTML5 Audio element.
  </audio>
  
- ### bdi
      <p dir="ltr">This arabic word <bdi>ARABIC_PLACEHOLDER</bdi> is automatically displayed right-to-left.</p>
      
- ### canvas
      <canvas id="myCanvas" width="300" height="200"></canvas>
      
- ### data
      <p>New Products</p>
      <ul>
          <li><data value="204">Green Tea</data></li>
          <li><data value="205">Tomato Ketchup</data></li>
          <li><data value="206">Roasted Coffee Beans</data></li>
      </ul>
      
- ### datalist
       <p>Enter your favorite browser name:</p>
       <input type="text" list="browsers">
       <datalist id="browsers">
          <option value="Firefox">
          <option value="Chrome">    
          <option value="Internet Explorer">
          <option value="Opera">
          <option value="Safari">
       </datalist>
 - ### details
       <details>
          <summary>What is HTML?</summary>
          <p>HTML is a markup language for describing the structure of web pages.</p>
      </details>
- ### dialog 
      <dialog open>
          <p>Are you sure you want to remove this item?</p>
          <button type="button">Yes</button>
          <button type="button">No</button>
      </dialog>
      
- ### embed
      <embed src="blur.swf" width="400px" height="200px">
      
- ### figcaption
      <figure>
          <img src="discovery.jpg" alt="Space Shuttle">
          <figcaption>NASA - Space Shuttle Discovery</figcaption>
      </figure>
- ### header
      <header>
          <h1>Tutorial Republic</h1>
          <nav>
              <p><a href="#">Home</a> | <a href="#">About</a> | <a href="#">Contact</a></p>
          </nav>
      </header>
- ### hgroup
       <hgroup>
          <h1>This is a main heading</h1>
          <h2>This is sub-heading</h2>
       </hgroup>
       
 - ### main
        <main>
            <div>Test</div>
        </main>
- ### mark
      <p>This is some <mark>highlighted</mark> text.</p>
      <p>Here are <mark>some more highlighted</mark> text.</p>
- ### menuitem
- ### output
      <form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
          <input type="range" id="a" value="50"> +
          <input type="number" id="b" value="100"> =
          <output name="result" for="a b"></output>
      </form>
 - ### picture
		<picture>
			<source media="(min-width: 1024px)" srcset="images/banner-large.png">
			<source media="(max-width: 768px)" srcset="images/banner-small.png">
			<img src="images/banner.png" alt="Banner">
		</picture>
- ### progress
	<progress id="bar" value="0" max="100"><span>0</span>%</progress>
- ### source
	<video controls="controls">
	    <source src="shuttle.mp4" type="video/mp4">
	    <source src="shuttle.ogv" type="video/ogg">
	    Your browser does not support the HTML5 Video element.
	</video>
- ### summary
	<details>
	    <summary>What is HTML?</summary>
	    <p>HTML is a markup language for describing the structure of web pages.</p>
	</details>
- ### svg
	<svg width="500" height="350">
	    <rect x="100" y="100" width="300" height="150" fill="yellow" stroke="black" stroke-width="5" />
	</svg>

- ### template
	<table id="studentsTable">
	    <thead>
		<tr>
		    <th>Roll No.</th>
		    <th>Student Name</th>
		</tr>
	    <thead>
	    <tbody>
		<!-- Content will be inserted here using template dynamically -->
	    <tbody>
	</table>

	<template id="studentRow">
	    <tr>
		<td></td>
		<td></td>
	    </tr>
	</template>
- ### time
   <p>The concert took place on <time datetime="2016-12-31 12:00">31 Dec</time>.</p>
