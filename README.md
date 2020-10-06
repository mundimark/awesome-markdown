Awesome Series @ Write Kit

[Markdown (Syntax & Extensions, Documentation & Cheat Sheets, Libraries, ...)](https://github.com/writekit/awesome-markdown) • 
[Markdown Editors & (Pre)viewers](https://github.com/writekit/awesome-markdown-editors)  •
[Books (Services, Hand-Written, Auto-Built w/ Open Data, ...)](https://github.com/writekit/awesome-books)


# Awesome Markdown

A collection of awesome markdown goodies (libraries, services, editors, tools, cheatsheets, etc.)

Note: :octocat: stands for the GitHub page and :gem: stands for the RubyGems page.

---

[ANNOUNCEMENT] Looking for the latest news, tools, tips & tricks, and more
about markdown and friends?
Follow along the Manuscripts News ([@manuscriptsnews](https://twitter.com/manuscriptsnews)) channel on twitter for updates.

---


#### _Contributions welcome. Anything missing? Send in a pull request. Thanks._


## Table of Contents

<!--

Generated with [markedpp](#markedpp). Get [nodejs](https://nodejs.org) first

1. $ npm i -g markedpp
2. $ markedpp --github -o README.md README.md

-->

<!-- !toc (minlevel=2 omit="Table of Contents") -->

* [Markdown](#markdown)
* [Markdown Syntax Extensions](#markdown-syntax-extensions)
  * [MultiMarkdown (MMD)](#multimarkdown-mmd)
  * [Markdown Extra](#markdown-extra)
  * [Markdown Extended (MDE)](#markdown-extended-mde)
* [Manuscripts](#manuscripts)
* [CommonMark](#commonmark)
* [GitHub Flavored Markdown (GFM)](#github-flavored-markdown-gfm)
* [Vanilla Flavored Markdown (VFMD)](#vanilla-flavored-markdown-vfmd)
* [Markdown Documentation](#markdown-documentation)
  * [Markdown Cheatsheets / Quick References](#markdown-cheatsheets--quick-references)
  * [Markdown Getting Started Guides / Tutorials](#markdown-getting-started-guides--tutorials)
* [Markdown Building Blocks](#markdown-building-blocks)
  * [Markdown Libraries & Tools](#markdown-libraries--tools)
  * [Babelmark](#babelmark)
  * [Markdown Style Guides / Best Practices](#markdown-style-guides--best-practices)
  * [Markdown Lint / Style Rule Checker](#markdown-lint--style-rule-checker)
  * [Markdown Web Components / Custom Elements](#markdown-web-components--custom-elements)
  * [Markdown to Website / Blog](#markdown-to-website--blog)
  * [Markdown to Email](#markdown-to-email)
  * [Markdown to Presentation / Slideshow](#markdown-to-presentation--slideshow)
  * [Markdown to Portable Document Format (PDF)](#markdown-to-portable-document-format-pdf)
  * [Markdown Styles / Documents / Pages](#markdown-styles--documents--pages)
  * [Markdown to Books](#markdown-to-books)
  * [Markdown to Table of Contents (TOC)](#markdown-to-table-of-contents-toc)
  * [Markdown to Markdown Pre-Processor](#markdown-to-markdown-pre-processor)
* [Convert to Markdown Tools](#convert-to-markdown-tools)
  * [Microsoft Word to Markdown](#microsoft-word-to-markdown)
  * [Hypertext Markup Language (HTML) to Markdown](#hypertext-markup-language-html-to-markdown)
  * [Source Code to Markdown](#source-code-to-markdown)
  * [Technical Documentation to Markdown](#technical-documentation-to-markdown)
* [Book Services](#book-services)
* [Articles](#articles)
* [Meta](#meta)

<!-- toc! -->

## Markdown

_email-style writing for the web by John Gruber and Aaron Swartz_ 

- **Markdown** (web: [daringfireball.net/projects/markdown](http://daringfireball.net/projects/markdown)) - original Markdown syntax write-up and processor in Perl by John Gruber; no longer maintained (last update in December 2004)

History / Genesis

- [Introducing Markdown](http://daringfireball.net/2004/03/introducing_markdown) by John Gruber - March 15, 2004

  >   I've written a text-to-HTML formatting tool called Markdown, which is now available for download.
  > Markdown allows web writers to compose text using a simple, readable, plain text formatting syntax;
  > Markdown takes care of translating it to valid XHTML (or, if you prefer, HTML).

- [Dive into Markdown](http://daringfireball.net/2004/03/dive_into_markdown) by John Gruber - March 19, 2004

  >  You don't need to "preview" an email before you send it -- you write it, you read it, you edit it, right there.
  >
  >  In fact, I love writing email. Email is my favorite writing medium. I've sent over 16,000 emails in the last five years. 
  > The conventions of plain text email allow me to express myself clearly and precisely, without ever getting in my way.
  >
  > Thus, Markdown. Email-style writing for the web.

- [Markdown](http://www.aaronsw.com/weblog/001189) by Aaron Swartz - March 22, 2004

  >    For months I've been working with John Gruber on a new project. The idea was to make writing simple web pages,
  > and especially weblog entries, as easy as writing an email, by allowing you to use much the same syntax and converting it 
  > automatically into HTML.
  >
  >   Together we pored over the syntax details from top to bottom, trying to develop the perfect format, 
  > and I think we've got something pretty darn great. We've tested it extensively: on our blogs, in my comments form, in our emails.


<!--
- [**Talk**](https://pairlist6.pair.net/mailman/listinfo/markdown-discuss) - markdown-discuss mailing list
    no longer in use
  -->

Documentation

- [**Markdown @ Wikipedia**](http://en.wikipedia.org/wiki/Markdown)


## Markdown Syntax Extensions

- [SmartyPants](http://daringfireball.net/projects/smartypants) -  convert (c) into ?, "" into ?, etc. 
- [Emojis](http://www.emoji-cheat-sheet.com) - [:octocat:](https://github.com/arvida/emoji-cheat-sheet.com)
- [CriticMarkup](http://criticmarkup.com) - [:octocat:](https://github.com/CriticMarkup)
- [GitHub Flavored Markup (GFM)](https://help.github.com/articles/github-flavored-markdown) - @mention, to do lists w/ [ ] and [x], etc.

### MultiMarkdown (MMD)

- [MultiMarkdown (MMD)](http://fletcherpenney.net/multimarkdown) - Markdown extensions by Fletcher Penney adding footnotes, tables, definition lists, document metadata (e.g. title, author, date, etc.) and more; first added to MultiMarkdown.pl
    - [Cheatsheet](https://rawgit.com/fletcher/human-markdown-reference/master/index.html)  - syntax quick reference
    - [Test Suite :octocat:](https://github.com/fletcher/MMD-Test-Suite)
- [MultiMarkdown.pl :octocat:](https://github.com/fletcher/MultiMarkdown) - historic MultiMarkdown.pl code; converter script in Perl (last update in Jan 2011)

### Markdown Extra

- [Markdown Extra](https://michelf.ca/projects/php-markdown/extra/) - Markdown extensions by Michel Fortin; first added to PHP Markdown (Extra)
- [Dingus](https://michelf.ca/projects/php-markdown/dingus/)  - try Markdown Extra in your browser

### Markdown Extended (MDE)

- [Markdown Extended (MDE) @ aboutmde.org](http://aboutmde.org)
    - [Spec](http://manifest.aboutmde.org)
    - [Cheatsheet](http://cheatsheet.aboutmde.org/) - syntax quick reference; examples side-by-side
    - [Dingus](http://dingus.aboutmde.org) - try Markdown Extended in your browser
- [Code :octocat:](https://github.com/piwi/markdown-extended) - converter script in PHP


## Manuscripts

_Free book format for Markdown_

**Manuscripts**
(web: [`manuscripts.github.io`](http://manuscripts.github.io),
 github: [`manuscripts`](https://github.com/manuscripts)) -
adds book.yml for book (meta) info e.g. title, author, publisher, year etc.
and contents.yml for table of contents and file structure

- Manuscripts Book Starter Kit (github: [`manuscripts/book-starter`](https://github.com/manuscripts/book-starter))



## CommonMark

_A strongly specified, highly compatible implementation of Markdown_

**CommonMark**
(web: [`commonmark.org`](http://commonmark.org))

- Spec (web: [`spec.commonmark.org`](http://spec.commonmark.org)) - Edited by John MacFarlane 
- Dingus (web: [`spec.commonmark.org/dingus`](http://spec.commonmark.org/dingus)) - try CommonMark in your browser
- Talk (web: [`talk.commonmark.org`](http://talk.commonmark.org))
- Code (github: [`jgm/CommonMark`](https://github.com/jgm/CommonMark)) - spec and reference code in JavaScript and C

## GitHub Flavored Markdown (GFM)

_CommonMark with GitHub Extensions_

**GitHub Flavored Markdown (GFM)**

- Spec (web: [`github.github.com/gfm`](https://github.github.com/gfm))
- Code (github: [`github/cmark`](https://github.com/github/cmark) - reference code in C (fork of cmark w/ extensions)

Extensions include:

Leaf Blocks: Tables ++ 
Container Blocks: Task list items ++
Inlines: Strikethrough; Autolinks; Disallowed Raw HTML


## Vanilla Flavored Markdown (VFMD)

_A variant of Markdown with an unambiguous specification of its syntax_ 

**Vanilla Flavored Markdown (VFMD)**
(web: [`vfmd.org`](http://www.vfmd.org), github: [`vfmd`](https://github.com/vfmd))

- Spec (web: [vfmd.org/vfmd-spec/specification](http://www.vfmd.org/vfmd-spec/specification)) - Edited by Roopesh Chander
- Code (github: [`vfmd/vfmd-src`](https://github.com/vfmd/vfmd-src)) - reference code in C++

Differences include:

Intra-word emphasis;
Simplified reference link/image syntax;
Lists and the 4-space rule;
Better automatic link detection;
Double blank lines as end of blocks;
Starting number in lists; 
Misnested constructs; 
Including raw HTML;
Character encoding



## Markdown Documentation

### Markdown Cheatsheets / Quick References

- [Markdown Cheatsheet :octocat:](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Markdown Getting Started Guides / Tutorials

- [Markdown Tutorial](http://markdowntutorial.com) - [:octocat:](https://github.com/gjtorikian/markdowntutorial.com)
- [Mastering Markdown @ GitHub Guides](https://guides.github.com/features/mastering-markdown)
- [Markdown Basics @ GitHub Help](https://help.github.com/articles/markdown-basics)
- [Markdown Guide](https://www.markdownguide.org/)



## Markdown Building Blocks

### Markdown Libraries & Tools

<a name="pandoc"></a>

**Pandoc**
(web: [`pandoc.org`](http://pandoc.org),
 github: [github.com/jgm/pandoc](https://github.com/jgm/pandoc)) -
a universal document converter (in Haskell)


**kramdown**
(web: [`kramdown.gettalong.org`](http://kramdown.gettalong.org),
 github: [`gettalong/kramdown`](https://github.com/gettalong/kramdown),
 gem: [`kramdown`](https://rubygems.org/gems/kramdown)) -
markdown library & command line tool (in Ruby)


**Markdown Extended (MDE)**
(github: [`e-picas/markdown-extended`](https://github.com/e-picas/markdown-extended)
- transform plain text input (strings or files) in various output formats (in PHP)

<a name="marked"></a>

**marked**
(web: [`marked.js.org`](https://marked.js.org), github: [marked :octocat:](https://github.com/markedjs/marked)) a markdown parser and compiler. Built for speed. (In Javascript)


<a name="markdown-it"></a>

**markdown-it**
(web: [`markdown-it.github.io`](https://markdown-it.github.io/), github: [markdown-it :octocat:](https://github.com/markdown-it/markdown-it)) Javascript markdown parser. 100% CommonMark support, extensions, syntax plugins & high speed.
Is extensible with [plugins](https://www.npmjs.com/search?q=keywords:markdown-it-plugin).

**concat-md**
([npm](https://www.npmjs.com/package/concat-md), [github](https://github.com/ozum/concat-md#readme)) CLI and API to concatenate markdown files and modify as necessary. Also adds titles from FrontMatter, file names and directory names, decreases level of existing titles to comply with added titles.

### Babelmark

- [Babelmark 2]() - a tool for comparing the output of various implementations of Markdown syntax
    - [Babelmark 2 F.A.Q.](http://johnmacfarlane.net/babelmark2/faq.html) - frequently asked questions (and answers) e.g. ... ??


### Markdown Style Guides / Best Practices

to be done

### Markdown Lint / Style Rule Checker

- [markdownlint](https://github.com/DavidAnson/markdownlint) - A Node.js style checker and lint tool for Markdown/CommonMark files offering a good set of defaults. Allows for customization.
- [mdformat](https://github.com/executablebooks/mdformat) - CommonMark compliant Markdown formatter
- [mdlint]() to be done
- [vscode-markdownlint](https://github.com/DavidAnson/vscode-markdownlint) - [Visual Studio Code Plugin](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) enabling in-place linting of markdown files.


### Markdown Web Components / Custom Elements

- [`<x-markdown>`]() - to be done




### Markdown to Website / Blog

**Jekyll**
(web: [`jekyllrb.com`](http://jekyllrb.com),
 github: [`jekyll/jekyll` :octocat:](https://github.com/jekyll/jekyll),
 gem: [`jekyll` :gem:](https://rubygems.org/gems/jekyll)) -
transform your plain text into static websites and blogs (in Ruby)

**Middleman**
(web: [`middlemanapp.com`](https://middlemanapp.com),
 github: [`middleman/middleman` :octocat:](https://github.com/middleman/middleman),
 gem: [`middleman` :gem:](https://rubygems.org/gems/middleman)) -
makes developing websites simple (in Ruby)

**Slate** (github: [lord/slate :octocat:](https://github.com/lord/slate)) - beautiful API documentation, based on **Middleman**

**Shins** (github: [`Mermade/shins` :octocat:](https://github.com/Mermade/shins), npm: [`shins`](https://www.npmjs.com/package/shins)) – beautiful API documentation, with node.js (port of **Slate**)

**md-fileserver** (github: [md-fileserver :octocat:](https://github.com/commenthol/md-fileserver), npm: [`md-fileserver`](https://www.npmjs.com/package/md-fileserver)) – View markdown files locally in browser.

### Markdown to Email

**Markdown Here**
(web: [`markdown-here.com`](http://markdown-here.com),
 github: [`adam-p/markdown-here`](https://github.com/adam-p/markdown-here)) -
a browser extension for rendering email written in Markdown;
available for Chrome, Firefox, Safari, Thunderbird, and more;
besides email also works with Evernote, Google Groups, Blogger, and more



### Markdown to Presentation / Slideshow

**Slide Show (S9)**
(web: [`slideshow-s9.github.io`](http://slideshow-s9.github.io),
 github: [`slideshow-s9/slideshow`](https://github.com/slideshow-s9),
 gem: [`slideshow`](https://rubygems.org/gems/slideshow)) -
a free web alternative to PowerPoint and Keynote in Ruby

- Templates (github: [`slideshow-templates`](https://github.com/slideshow-templates))

**Markpress** (github: [`markpress`](https://github.com/gamell/markpress)) - A command line tool and node package to convert markdown files into self-contained [impressjs](https://github.com/impress/impress.js/) html presentations. [Example](https://gamell.github.io/markpress) 

**nodePPT** (github: [`nodePPT`](https://github.com/ksky521/nodePPT)) - A web presentation tool supporting markdown based on GFM.

**Deckset** (website: [Deckset](http://www.decksetapp.com)) – A macOS desktop app that renders Markdown presentations in beautifully designed templates.

**GitPitch** (website: [GitPitch](http://gitpitch.com/), github: [gitpitch :octocat:](https://github.com/gitpitch/gitpitch/)) – Markdown Presentations For Everyone on GitHub, GitLab, Bitbucket, GitBucket, Gitea, and Gogs. [Example](https://gitpitch.com/gitpitch/gitpitch/master)

### Markdown to Portable Document Format (PDF)

- [markdown-pdf :octocat:](https://github.com/alanshaw/markdown-pdf), [(npm Package)](https://www.npmjs.com/package/markdown-pdf) -  converts Markdown files to PDFs


### Markdown Styles / Documents / Pages

**The Zen of Page Designs**
(github: [`pagedesigns`](https://github.com/pagedesigns))


### Markdown to Books

**The Zen of Book Designs**
(github: [`bookdesigns`](https://github.com/bookdesigns))



**Hyper Book (H9)** [:octocat:](https://github.com/hybook), [:gem:](https://rubygems.org/gems/hybook)

- [Templates :octocat:](https://github.com/book-templates)



### Markdown to Table of Contents (TOC)

* **Generate a markdown table of contents (TOC) with [remarkable](https://github.com/jonschlinkert/remarkable)**
  (github: [`markdown-toc`](https://github.com/jonschlinkert/markdown-toc)) 
* [markedpp](#markedpp) Markdown to Markdown Pre-Processor
* [mdtoc :octocat:](https://github.com/tallclair/mdtoc) - Standalone TOC generator designed for CI


### Markdown to Markdown Pre-Processor

<a name="markedpp"></a>

* **markedpp** (github: [markedpp :octocat:](https://github.com/commenthol/markedpp)) adds support for table-of-contents (TOC), numbered headings, includes other markdown files and/or create reference lists for use with different markdown processors like [marked](#marked), [markdown-it](#markdown-it), [pandoc](#pandoc) or for hosting on github.com, gitlab.com, bitbucket.org or ghost.org.


## Convert to Markdown Tools

### Microsoft Word to Markdown

- [word-to-markdowm gem :octocat:](https://github.com/benbalter/word-to-markdown), [:gem:](https://rubygems.org/gems/word-to-markdown) - "liberate" content from the jail that is Microsoft Word documents; converts to plain-text Markdown

### Hypertext Markup Language (HTML) to Markdown

Ruby

- [reverse_markdown :octocat:](https://github.com/xijo/reverse_markdown), [:gem:](https://rubygems.org/gems/reverse_markdown) - map simple HTML back into markdown
- [html2markdown :octocat:](https://github.com/29decibel/html2markdown), [:gem:](https://rubygems.org/gems/html2markdown) - simple and flexible HTML to markdown converter
- [hypertextmarkdown :octocat:](https://github.com/jcheatham/hypertextmarkdown), [:gem:](https://rubygems.org/gems/hypertextmarkdown) - HTML to markdown converter
- [html2md :octocat:](https://github.com/pmorton/html2md), [:gem:](https://rubygems.org/gems/html2md) - converts basic HTML to markdown 
- [unmarkdown :octocat:](https://github.com/soffes/unmarkdown), [:gem:](https://rubygems.org/gems/unmarkdown) - convert HTML to Markdown
- [upmark :octocat:](https://github.com/conversation/upmark), [:gem:](https://rubygems.org/gems/upmark) - a HTML to Markdown converter
- [remark :octocat:](https://github.com/mislav/remark) - HTML to Markdown converter in Ruby


JavaScript / Node.js

- [to-markdown :octocat:](https://github.com/domchristie/to-markdown), [(npm Package)](https://www.npmjs.com/package/to-markdown)  - a HTML to Markdown converter in JavaScript
- [html2markdown :octocat:](https://github.com/alexgorbatchev/html2markdown),  [(npm Package)](https://www.npmjs.com/package/html2markdown) -  converting HTML to Markdown
- [Markitdown](http://markitdown.medusis.com) - A client side web app that lets you paste formatted text from a webpage (e.g with links intact) and recieve markdown output.
  - [Markitdown.medusis.com :octocat:](https://github.com/bambax/markitdown.medusis.com) - A client side web app for converting rich text to markdown

More

- [heckyesmarkdown.com](http://heckyesmarkdown.com) - instantly convert a webpage to markdown; the service presents a simple interface that converts any reasonable web page into markdown (note: the service seems to use the Readability API to remove all the non-content cruft from the source page before proceeding with markdownification)

### Source Code to Markdown

Generate API documentation from source code in Markdown, then host it on the web using one of the many [Markdown to Website](#markdown-to-website--blog) tools to host and serve it.

- [widdershins :octocat:](https://github.com/Mermade/widdershins) - turn [OpenAPI/Swagger](https://www.openapis.org) REST API documentation to Markdown
- [Moxygen :octocat:](https://github.com/sourcey/moxygen) - [Doxygen](http://www.stack.nl/~dimitri/doxygen/) (C++, but also supports other popular programming languages such as C, Objective-C, C#, PHP, Java, Python, IDL , Fortran, VHDL, Tcl, and to some extent D.) documentation to Markdown
- [raml2html/markdown-theme :octocat:](https://github.com/raml2html/markdown-theme) - turn [RAML](http://raml.org) REST API documentation to Markdown using raml2html
- [jsdoc-to-markdown :octocat:](https://github.com/jsdoc2md/jsdoc-to-markdown) - JavaScript API documentation via JSDoc to Markdown
- [mmarkdown :octocat:](https://github.com/albinotonnina/mmarkdown) - Interpret mmd fenced code blocks in a markdown file and generate a cooler version of it.

### Technical Documentation to Markdown

- [dita-ot-markdown](https://github.com/jelovirt/dita-ot-markdown) – converts DITA into Markdown, integrates with standard DITA OT tool chain 

### Screencast to Markdown

- [Paircast](https://paircast.io) - Combines desktop video, git diffs, and voice transcriptions in to markdown documentation.

## Book Services

- [Softcover.io](https://www.softcover.io) - publish from the comfort of your command-line by Michael Hartl et al 
    - [Softcover :octocat:](https://github.com/softcover/softcover), [:gem:](https://rubygems.org/gems/softcover) - a command line tool for book generation, building, and publishing 
- [GitBook.com](https://www.gitbook.com)  - write and publish books with Markdown and Git by Samy Pessé et al
    - [GitBook :octocat:](https://github.com/GitbookIO/gitbook) - a command line tool (and Node.js library) for building beautiful books using GitHub/Git and Markdown (or AsciiDoc)
    
<!-- break -->

- [Bitbooks.cc (discontinued; archived)](https://github.com/bitbooks) - Bitbooks turns a repo full of markdown files into a handsome, hosted, online book - by Bryan Braun
    - [Franklin :octocat:](https://github.com/bryanbraun/franklin) - a static-site framework, optimized for online books



## Articles

- [Why You Shouldn't Use Markdown for Documentation](http://ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs) by Eric Holscher, March 2016
- [Stop Using Markdown For Documentation](https://mister-gold.pro/posts/en/asciidoc-vs-markdown/) by Anton Zolotukhin, April 2018
- [Why isn't there a formal grammar for Markdown?](http://roopc.net/posts/2014/markdown-cfg) by Roopesh Chander, September 2014


## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the markdown-discuss mailing list. Thanks!

