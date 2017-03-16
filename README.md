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


## Markdown

- **Markdown** (web: [daringfireball.net/projects/markdown](http://daringfireball.net/projects/markdown)) - original Markdown syntax write-up and processor in Perl by John Gruber; no longer maintained (last update in Dec 2004)
    - [**Talk**](https://pairlist6.pair.net/mailman/listinfo/markdown-discuss) - markdown-discuss mailing list

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
and contents.yml for table of contents and file strucutre

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



## Markdown Building Blocks

### Markdown Libraries & Tools

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




### Babelmark

- [Babelmark 2]() - a tool for comparing the output of various implementations of Markdown syntax
    - [Babelmark 2 F.A.Q.](http://johnmacfarlane.net/babelmark2/faq.html) - frequently asked questions (and answers) e.g. ... ??


### Markdown Style Guides / Best Practices

to be done

### Markdown Lint / Style Rule Checker

- [mdlint]() to be done



### Markdown Web Components / Custom Elements

- [`<x-markdown>`]() - to be done




### Markdown to Website / Blog

**Jekyll**
(web: [`jekyllrb.com`](http://jekyllrb.com),
 github: [`jekyll/jekyll`](https://github.com/jekyll/jekyll),
 gem: [`jekyll`](https://rubygems.org/gems/jekyll)) -
transform your plain text into static websites and blogs (in Ruby)

**Middleman**
(web: [`middlemanapp.com`](https://middlemanapp.com),
 github: [`middleman/middleman`](https://github.com/middleman/middleman),
 gem: [`middleman`]) -
makes developing websites simple (in Ruby)



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

**nodePPT** (github: [`nodePPT`](https://github.com/ksky521/nodePPT) - A web presentation tool supporting markdown based on GFM.

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

**Generate a markdown table of contents (TOC) with [remarkable](https://github.com/jonschlinkert/remarkable)**
(github: [`markdown-toc`](https://github.com/jonschlinkert/markdown-toc))




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
 

## Book Services

- [Softcover.io](https://www.softcover.io) - publish from the comfort of your command-line
    - [Softcover :octocat:](https://github.com/softcover/softcover), [:gem:](https://rubygems.org/gems/softcover) - a command line tool for book generation, building, and publishing 
- [GitBook.com](https://www.gitbook.com)  - write and publish books with Markdown and Git
    - [GitBook :octocat:](https://github.com/GitbookIO/gitbook) - a command line tool (and Node.js library) for building beautiful books using GitHub/Git and Markdown (or AsciiDoc)
- [Bitbooks.cc](http://bitbooks.cc) - Bitbooks turns a repo full of markdown files into a handsome, hosted, online book
    - [Franklin :octocat:](https://github.com/bryanbraun/franklin) - a static-site framework, optimized for online books



## Articles 

- [Why You Shouldn't Use Markdown for Documentation](http://ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs) by Eric Holscher, March 2016
- [Why isn't there a formal grammar for Markdown?](http://roopc.net/posts/2014/markdown-cfg) by Roopesh Chander, September 2014


## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the markdown-discuss mailing list. Thanks!

