<h1 id="top">Contents</h1>
- <h3>Typography</h3>
	- [Headings](#headings-top)
	- [Paragraphs](#paragraphs-top)
	- [Bold Text](#bold-text-top)
	- [Italicized Text](#italicized-text-top)
	- [Block Quotes](#blockquotes-top)
	- [Lists](#lists-top)
- <h3>Links</h3>
	- [Inline Links](#inline-link-top)
	- [Reference Links](#reference-links-top)
- <h3>Tables</h3>
	- [Standard Table](#standard-table-top)
- <h3>Code</h3>
	- [Inline Code](#inline-code-top)
	- [Code Blocks](#code-blocks-top)
- <h3>Images</h3>
	- [Inline Images](#inline-images-top)
	- [Image References](#image-references-top)
- <h3>Other</h3>
	- [Horizontal Rules](#horizontal-rules-top)
	- [Backslash Escape Characters](#backslash-escape-characters-top)

# Typography
<h3 id="heading">Headings <a href="#top">(top)</a></h3>
```plain
<h1> = # Header
<h2> = ## Header
<h3> = ### Header
<h4> = #### Header
<h5> = ##### Header
<h6> = ###### Header
```

<h3 id="paragraph">Paragraphs <a href="#top">(top)</a></h3>
```plain
This is the first paragraph.

And this is the second separated by a blank line.

```

<h3 id="bold">Bold Text <a href="#top">(top)</a></h3>
```plain
In this sentence the word **bold** is tagged with <strong> tags.
```

<h3 id="italic">Italicized Text <a href="#top">(top)</a></h3>
```plain
In this sentence the word *italics* is tagged with <em> tags.
```

<h3 id="blockquote">Blockquotes <a href="#top">(top)</a></h3>
```plain
/***********************************
* Standard Blockquote
***********************************/
> This is a block
> of really cool
> text

/***********************************
* Nested Blockquote
***********************************/
> Here is a block
> that contains
>> a nest!
> and I'm back out of the nest...
```

<h3 id="list">Lists <a href="#top">(top)</a></h3>
```plain
/***********************************
* Unordered List
***********************************/
- list item 1
- list item 2
	- sublist 1
	- sublist 2
- list item 3

/***********************************
* Ordered List
***********************************/
1. list item 1
2. list item 2
	1. sublist 1
	2. sublist 2
3. list item 3

```

# Links
<h3 id="inlinelink">Inline Link <a href="#top">(top)</a></h3>
```plain
This is a line with an [inline link to Google](http://www.google.com "Google").
```

<h3 id="reflink">Reference Links <a href="#top">(top)</a></h3>
```plain
This line has reference links for [Google] [1] and [GitHub] [2].

	[1]: http://www.google.com "Google"
	[2]: http://www.github.com "GitHub"
```

# Tables
<h3 id="table">Standard Table <a href="#top">(top)</a></h3>
```plain
| Header 1 | Header 2     |
| -------- | ------------ |
| Content  | More content |
```

# Code
<h3 id="inlinecode">Inline Code <a href="#top">(top)</a></h3>
```plain
Here is some inline `code` that will be formatted appropriately
```

<h3 id="codeblock">Code Blocks <a href="#top">(top)</a></h3>
```plain
/***********************************
* Standard Code Block
***********************************/
Tab or four spaces for standard code block syntax:
	void replace(){
		//lots of really cool code in here
	}

/******************************************************
* GitHub Flavored Code Block with Syntax Highlighting
*******************************************************/
Three ticks before and after the code block & specify language:
	```language
	void replace(){
		//lots of really cool code in here
	}
	```
```

# Images
<h3 id="inlineimg">Inline Images <a href="#top">(top)</a></h3>
```plain
![alt text](path/to/img.jpg "Title")
```
<h3 id="refimg">Image References <a href="#top">(top)</a></h3>
```plain
![alt text][id]

	[id]: path/to/img.jpg "Title"
```

# Other
<h3 id="horiz">Horizontal Rules <a href="#top">(top)</a></h3>
```plain
- - -
```

<h3 id="backslash">Backslash Escape Characters <a href="#top">(top)</a></h3>
```plain
\   backslash
`   backtick
*   asterisk
_   underscore
{}  curly braces
[]  square brackets
()  parentheses
#   hash mark
+   plus sign
-   minus sign (hyphen)
.   dot
!   exclamation mark
```
