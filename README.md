# awesome-markdown

A collection of awesome markdown goodies, libraries, services, tools, guides, books, etc.

Note: :gem: stands for the RubyGems page and :octocat: stands for the GitHub page.

---
---

Contributions welcome. Anything missing? Send in a pull request. Thanks.

## Markdown

- [Markdown](http://daringfireball.net/projects/markdown) - original Markdown syntax write-up and processor in Perl by John Gruber; no longer maintained (last update in Dec 2004)
- [Talk](https://pairlist6.pair.net/mailman/listinfo/markdown-discuss) - markdown-discuss mailing list

Documentation

- [Markdown @ Wikipedia](http://en.wikipedia.org/wiki/Markdown)


## Markdown Syntax Extensions

- [MultiMarkdown (MMD)](http://fletcherpenney.net/multimarkdown) - Markdown extensions by Fletcher Penney adding footnotes, tables, definition lists, document metadata (e.g. title, author, date, etc.) and more


## CommonMark

_A strongly specified, highly compatible implementation of Markdown_

- [commonmark.org](http://commonmark.org)
- [Spec](http://spec.commonmark.org)
- [Code :octocat:](https://github.com/jgm/CommonMark) - spec and reference code in JavaScript and C
- [Dingus](http://spec.commonmark.org/dingus) - try CommonMark (live) in your browser
- [Talk](http://talk.commonmark.org)


## Markdown Libraries

- [kramdown](http://kramdown.gettalong.org) - [:octocat:](https://github.com/gettalong/kramdown), [:gem:](https://rubygems.org/gems/kramdown) - markdown library (in Ruby)


## Markdown Tools

- [Pandoc](http://pandoc.org) - [:octocat:](https://github.com/jgm/pandoc) - a universal document converter (in Haskell)
- [Jekyll](http://jekyllrb.com) - [:octocat:](https://github.com/jekyll), [:gem:](https://rubygems.org/gems/jekyll) - transform your plain text into static websites and blogs (in Ruby)
- [Middleman](https://middlemanapp.com) - [:octocat:](https://github.com/middleman/middleman), [:gem:](https://rubygems.org/gems/middleman) - makes developing websites simple (in Ruby)


### Markdown to Website / Blog



### Markdown to Email

- [Markdown Here](http://markdown-here.com) - [:octocat:](https://github.com/adam-p/markdown-here) - a browser extension for rendering email written in Markdown; available for Chrome, Firefox, Safari, Thunderbird, and more; besides email also works with Evernote, Google Groups, Blogger, and more


### Markdown to Presentation / Slideshow

- [Slide Show (S9)](http://slideshow-s9.github.io) - [:octocat:](https://github.com/slideshow-s9), [:gem:](https://rubygems.org/gems/slideshow) - a free web alternative to PowerPoint and Keynote in Ruby
    - [Templates :octocat:](https://github.com/slideshow-templates)

### Markdown to Portable Document Format (PDF)

- [markdown-pdf :octocat:](https://github.com/alanshaw/markdown-pdf), [(npm Package)](https://www.npmjs.com/package/markdown-pdf) -  converts Markdown files to PDFs


### Markdown to Books

- [Hyper Book (H9) :octocat:](https://github.com/hybook), [:gem:](https://rubygems.org/gems/hybook)
    - [Templates :octocat:](https://github.com/book-templates)


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
 
Command Line Examples

Pandoc

~~~
$ pandoc file.html -o file.md
~~~

kramdown

~~~
$ kramdown --input html --output kramdown file.html > file.md
~~~


## Real World "Hand-Written" Book Examples

- [Open Data Handbook, 2nd Edition](http://opendatahandbook.org) - [:octocat:](https://github.com/okfn/opendatahandbook-v2) - note: 1st edition in reStructedText, 2nd edtion in markdown
- [Pro Git, 2nd Edition](http://git-scm.com/book) - [:octocat:](https://github.com/progit/progit2) - note: 1st edition in markdown, 2nd edition in asciidoc
- [PHP - The Right Way](http://www.phptherightway.com) - [:octocat:](https://github.com/codeguy/php-the-right-way)
- [The Front-End Tooling Book](http://tooling.github.io/book-of-modern-frontend-tooling) - [:octocat:](https://github.com/tooling/book-of-modern-frontend-tooling)
- [Go Bootcamp](http://www.golangbootcamp.com/book) - [:octocat:](https://github.com/GoBootcamp/book)


## Open Data "Auto-Build" Book Examples

- [Free World Beer Book](http://openbeer.github.io/book) - [:octocat:](https://github.com/openbeer/book) - work-in-progress; auto-build using the beer.db and markdown templates w/ a static site generator
    - [Templates :octocat:](https://github.com/book-templates/beer) 


## Book Services

- [Softcover.io](https://www.softcover.io) - publish from the comfort of your command-line
    - [Softcover :octocat:](https://github.com/softcover/softcover), [:gem:](https://rubygems.org/gems/softcover) - a command line tool for book generation, building, and publishing 
- [GitBook.com](https://www.gitbook.com)  - write and publish books with Markdown and Git
    - [GitBook :octocat:](https://github.com/GitbookIO/gitbook) - a command line tool (and Node.js library) for building beautiful books using GitHub/Git and Markdown (or AsciiDoc)
- [Bitbooks.cc](http://bitbooks.cc) - Bitbooks turns a repo full of markdown files into a handsome, hosted, online book
    - [Franklin :octocat:](https://github.com/bryanbraun/franklin) - a static-site framework, optimized for online books


## Alternatives

_More lightweight markup languages_

- [Wikitext, Wikicode](http://en.wikipedia.org/wiki/Help:Wiki_markup) - wiki markup used by Wikipedia and friends
   - [Creole](http://en.wikipedia.org/wiki/Creole_(markup))  - "Standardized" core Wikitext markup
- [AsciiDoc](http://en.wikipedia.org/wiki/AsciiDoc)
- [Textile](http://en.wikipedia.org/wiki/Textile_(markup_language))
- [reStructuredText (rst, reST)](http://en.wikipedia.org/wiki/ReStructuredText)
- [BBCode](http://en.wikipedia.org/wiki/BBCode) - bulletin board code


## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the markdown-discuss mailing list. Thanks!

