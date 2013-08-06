<h1 id="top">Contents</h1>
- <span style="font-size:22px;">Typography</span>
	- [Headings](#heading)
	- [Paragraphs](#paragraph)
	- [Bold Text](#bold)
	- [Italicized Text](#italic)
	- [Block Quotes](#blockquote)
	- [Lists](#list)
- <span style="font-size:22px;">Links</span>
	- [Inline Links](#inlinelink)
	- [Reference Links](#reflink)
- <span style="font-size:22px;">Tables</span>
	- [Standard Table](#table)
- <span style="font-size:22px;">Code</span>
	- [Inline Code](#inlinecode)
	- [Code Blocks](#codeblock)
- <span style="font-size:22px;">Images</span>
	- [Inline Images](#inlineimg)
	- [Image References](#refimg)
- <span style="font-size:22px;">Other</span>
	- [Horizontal Rules](#horiz)

# Typography
<h3 id="heading">Headings <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Heading Markdown http://daringfireball.net/projects/markdown/syntax#header Gruber Docs
<h1> = # Header
<h2> = ## Header
<h3> = ### Header
<h4> = #### Header
<h5> = ##### Header
<h6> = ###### Header
```

<h3 id="paragraph">Paragraphs <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Paragraph Markdown
This is the first paragraph.

And this is the second separated by a blank line.

```

<h3 id="bold">Bold Text <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Bold Text Markdown
In this sentence the word **bold** is tagged with &lt;strong&gt; tags.
```

<h3 id="italic">Italicized Text <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Italicized Text
In this sentence the word *italics* is tagged with &lt;em&gt; tags.
```

<h3 id="blockquote">Blockquotes <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Blockquotes Markdown http://daringfireball.net/projects/markdown/syntax#blockquote Gruber Docs
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

<h3 id="list">Lists <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Lists Markdown http://daringfireball.net/projects/markdown/syntax#list Gruber Docs
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
<h3 id="inlinelink">Inline Link <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Inline Link Markdown
This is a line with an [inline link to Google](http://www.google.com "Google").
```

<h3 id="reflink">Reference Links <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Reference Links Markdown
This line has reference links for [Google] [1] and [GitHub] [2].

	[1]: http://www.google.com "Google"
	[2]: http://www.github.com "GitHub"
```

# Tables
<h3 id="table">Standard Table <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Standard Table Markdown
| Header 1 | Header 2     |
| -------- | ------------ |
| Content  | More content |
```

# Code
<h3 id="inlinecode">Inline Code <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Inline Code Markdown
Here is some inline `code` that will be formatted appropriately
```

<h3 id="codeblock">Code Blocks <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Code Block Markdown
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
<h3 id="inlineimg">Inline Images <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Inline Image Markdown
![alt text](path/to/img.jpg "Title")
```
<h3 id="refimg">Image References <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Image Reference Markdown
![alt text][id]

	[id]: path/to/img.jpg "Title"
```

# Other
<h3 id="horiz">Horizontal Rules <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Horizontal Rule Markdown
- - -
```

<h3 id="backslash">Backslash Escapes <a href="#top"><i class="icon-circle-arrow-up"></i></a></h3>
```plain Backslash Escape Characters
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
