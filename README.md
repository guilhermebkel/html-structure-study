# 📜  Html Structure Study
A deep study about the HTML Structure.

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