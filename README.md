# 📜  Html Structure Study
A deep study about the HTML Structure.

## Summary

- [ Core Tags ](#core-tags)
- [ Container Tags ](#container-tags)
- [ Textual Tags ](#textual-tags)
- [ Image Tags ](#image-tags)
- [ Multimedia Tags ](#multimedia-tags)
- [ Integrated Content Tags ](#integrated-content-tags)
- [ Formulary Tags ](#formulary-tags)
- [ Other Tags ](#other-tags)

<a name="core-tags"></a>

## Core Tags
```html
<!-- BODY -->
<body>
	<!-- HEADER  -->
	<header>
		<!-- NAV -->
		<nav>

		</nav>
	</header>

	<!-- MAIN -->
	<main>
		<!-- SECTION -->
		<section>
			<!-- ARTICLE -->
			<article>

			</article>
		</section>

		<!-- ASIDE -->
		<aside>
		</aside>
	</main>

	<!-- FOOTER -->
	<footer>

	</footer>
</body>
```
- **BODY**: The place where all the page data is put inside.

- **HEADER**: Generally we can use to add logos, titles, navigation menus, search fields, etc.

- **NAV**: Generally we can use to group links for other pages, sites. Besides, it can be even on header or footer, depending of what you're doing.

- **MAIN**: It is used to add the main content on the page. We have to make sure the page has only one single main tag.

- **SECTION**: It's a section inside a document and can have a new title composing inside.

- **ARTICLE**: Generally a independent content inside a page that can have other elements like header, footer and section inside.

- **ASIDE**: Usually used to show additional content like adverting, navigation, etc.

- **FOOTER**: Generally used  in the final of the page to describe content and author info.

<a name="container-tags"></a>

## Container Tags

- **SPAN**: Generic container in line.
```html
<span></span>
```

- **DIV**: Generic container in block.
```html
<div></div>
```

They must be used to group elements for styling and when there's no other element that is semantically for proper use.

<a name="textual-tags"></a>

## Textual Tags

- **P**: A text paragraph.
```html
<p>My paragraph</p>
```

- **A**: Defines a link between pages.
```html
<a href="https://other-page.com">
	Go to other page
</a>
```

- **OL**: Defines an ordered list.
```html
<ol></ol>
```

- **UL**: Defines an unordered list.
```html
<ul></ul>
```

- **LI**: Defines an item from some list.
```html
<ul>
	<li>first</li>
	<li>second</li>
</ul>
```

- **TIME**: Used to show time values.
```html
<time>05:00</time>
<time pubdate>2005-01-20</time>
<time datetime="2010-06-20 16:00">20 June</time>
```

- **ADDRESS**: Defines basically a contact info.
```html
<address>
	<h5>Be in touch</h5>
	<p>Street 01th</p>
	<p>+1 555 20852145</p>
</address>
```

- **CITE**: Defines a reference. It must includes a reference title or url.
```html
More info on <cite>[ISO-0101]</cite>
```

- **ABBR**: Used to show an abbreviation and some optional description for it.
```html
<p>Deep knowledge in
	<abbr title="Search Engine Optimization">
		SEO
	</abbr>
</p>
```

- **B**: Used on texts that need some spotlight with no explanation.
```html
My name is <b>Guilherme Mota</b>
```

- **STRONG**: Gives a spotlight to a word of high importance.
```html
The course will be available <strong>soon</strong>.
```

- **I**: Used to give spotlight for special words.
```html
The bug, in latin <i>Aedes Aegypti</i>.
```

- **EM**: Used on words that if you give some spotlight on a talk, they could really change all the meaning of it.
```html
This <em>isn't</em> an influence.
```

<a name="image-tags"></a>

## Image Tags

### Figure

```html
<figure>
	<img src="cat.png" alt="cat">
	<figcaption>Fig. 1 - A beautiful cat.</figcaption>
</figure>
```

- **FIGURE**: Defines a figure container.
- **FIGCAPTION**: Defines a figure description.
- **IMG**: Defines a image on document.

### Picture

```html
<picture>
	<source srcset="cat2.png" media="(min-width: 600px)" type="image/png" />
	<img src="cat1.png" alt="cat" />
</picture>
```

- **PICTURE**: It is a container used to specify multiple sources for a unique image.
- **SOURCE**: Used to specify different sources for some image.

<a name="multimedia-tags"></a>

## Multimedia Tags

```html
<video width="300" height="200" controls>
	<source src="running.mp4" type="video/mp4" />
	<source src="running.ogg" type="video/ogg" />
	<track src="subtitles.vtt" kind="subtitles" srclang="no" label="English"/>
</video>
```

- **AUDIO**: Used for sound content.
- **VIDEO**: Used for video content.
- **TRACK**: Used for subtitles for the current media being played.

<a name="integrated-content-tags"></a>

## Integrated Content Tags

- **IFRAME**: Used to incorporate other web documents inside some web document.
```html
<iframe></iframe>
```

- **EMBED**: Used to include pdf plugins and flash.
```html
<embed></embed>
```

<a name="formulary-tags"></a>

## Formulary Tags

### Form

```html
<form>
	<fieldset>
		<legend>Team name</legend>

		<div>
			<input type="radio" name="team" id="team_1" value="Chelsea" />
			<label for="team_1">Chelsea</label>
		</div>
	</fieldset>
</form>
```

- **FORM**: Used to submit data from user.
- **FIELDSET**: Used to group elements that represent the same idea.
- **LEGEND**: Explains the fieldset type.
- **LABEL**: Represents the label of some input.

---

### Input

- **INPUT**: A simple text field.
```html
<input id="username" type="text" name="username">
```

- **TEXTAREA**: A text field with multiple lines.
```html
<textarea id="story" name="username" rows="5" cols="33">
	Once upon a time...
</textarea>
```

- **SELECT**: Used to submit selected data from user.
```html
<select id="color" name="color">
	<option value="blue">Blue</option>
	<option value="red">Red</option>
</select>
```

- **BUTTON**: A simple clickable button.
```html
<button type="button" onclick="console.log('Hello!')">
	Hello?
</button>
```

<a name="other-tags"></a>

## Other Tags

### Summary

```html
<details>
	<summary>More details</summary>
	<p>Here goes the details...</p>
</details>
```

- **SUMMARY**: Summary defines a visible header for some detail text.
- **DETAILS**: Defines a text for some summary.

---

### Output

- **OUTPUT**: Show a result from an user action.
```html
<input type="number" name="a" value="10"> +
<input type="number" name="b" value="5"> =
<output name="result"></output>
```
