---
author-meta:
- John Doe
- Jane Roe
bibliography:
- content/manual-references.json
date-meta: '2020-05-15'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="Manuscript Title" />

  <meta name="citation_title" content="Manuscript Title" />

  <meta property="og:title" content="Manuscript Title" />

  <meta property="twitter:title" content="Manuscript Title" />

  <meta name="dc.date" content="2020-05-15" />

  <meta name="citation_publication_date" content="2020-05-15" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="John Doe" />

  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />

  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />

  <meta name="twitter:creator" content="@johndoe" />

  <meta name="citation_author" content="Jane Roe" />

  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />

  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />

  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />

  <link rel="canonical" href="https://essink.github.io/manubot_test/" />

  <meta property="og:url" content="https://essink.github.io/manubot_test/" />

  <meta property="twitter:url" content="https://essink.github.io/manubot_test/" />

  <meta name="citation_fulltext_html_url" content="https://essink.github.io/manubot_test/" />

  <meta name="citation_pdf_url" content="https://essink.github.io/manubot_test/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://essink.github.io/manubot_test/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://essink.github.io/manubot_test/v/8990e1238b27e4435a61c0e5282b7c3f2d7eb74f/" />

  <meta name="manubot_html_url_versioned" content="https://essink.github.io/manubot_test/v/8990e1238b27e4435a61c0e5282b7c3f2d7eb74f/" />

  <meta name="manubot_pdf_url_versioned" content="https://essink.github.io/manubot_test/v/8990e1238b27e4435a61c0e5282b7c3f2d7eb74f/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- markdown
- publishing
- manubot
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Manuscript Title
...






<small><em>
This manuscript
([permalink](https://essink.github.io/manubot_test/v/8990e1238b27e4435a61c0e5282b7c3f2d7eb74f/))
was automatically generated
from [essink/manubot_test@8990e12](https://github.com/essink/manubot_test/tree/8990e1238b27e4435a61c0e5282b7c3f2d7eb74f)
on May 15, 2020.
</em></small>

## Authors



+ **John Doe**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [johndoe](https://twitter.com/johndoe)<br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>



## Abstract {.page_break_before}




This manuscript is a template (aka "rootstock") for [Manubot](https://manubot.org/ "Manubot"), a tool for writing scholarly manuscripts.
Use this template as a starting point for your manuscript.

The rest of this document is a full list of formatting elements/features supported by Manubot.
Compare the input (`.md` files in the `/content` directory) to the output you see below.

## Basic formatting

**Bold** __text__

[Semi-bold text]{.semibold}

[Centered text]{.center}

[Right-aligned text]{.right}

*Italic* _text_

Combined *italics and __bold__*

~~Strikethrough~~

1. Ordered list item
2. Ordered list item
    a. Sub-item
    b. Sub-item
        i. Sub-sub-item
3. Ordered list item
    a. Sub-item

- List item
- List item
- List item

subscript: H~2~O is a liquid

superscript: 2^10^ is 1024.

[unicode superscripts](https://www.google.com/search?q=superscript+generator)⁰¹²³⁴⁵⁶⁷⁸⁹

[unicode subscripts](https://www.google.com/search?q=superscript+generator)₀₁₂₃₄₅₆₇₈₉

A long paragraph of text.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Putting each sentence on its own line has numerous benefits with regard to [editing](https://asciidoctor.org/docs/asciidoc-recommended-practices/#one-sentence-per-line) and [version control](https://rhodesmill.org/brandon/2012/one-sentence-per-line/).

Line break without starting a new paragraph by putting  
two spaces at end of line.

## Document organization

Document section headings:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

### A heading centered on its own printed page{.center .page_center}

<!-- an arbitrary comment. visible in input, but not visible in output. -->

Horizontal rule:

---

`Heading 1`'s are recommended to be reserved for the title of the manuscript.

`Heading 2`'s are recommended for broad sections such as *Abstract*, *Methods*, *Conclusion*, etc.

`Heading 3`'s and `Heading 4`'s are recommended for sub-sections.

## Links

Bare URL link: <https://manubot.org>

[Long link with lots of words and stuff and junk and bleep and blah and stuff and other stuff and more stuff yeah](https://manubot.org)

[Link with text](https://manubot.org)

[Link with hover text](https://manubot.org "Manubot Homepage")

[Link by reference][manubot homepage]

[Manubot Homepage]: https://manubot.org

## Citations

Citation by DOI [@doi:10.7554/eLife.32822].

Citation by PubMed Central ID [@pmcid:PMC6103790].

Citation by PubMed ID [@pmid:30718888].

Citation by Wikidata ID [@wikidata:Q56458321].

Citation by ISBN [@isbn:9780262517638].

Citation by URL [@url:https://greenelab.github.io/meta-review/].

Citation by tag [@tag:deep-review].

Multiple citations can be put inside the same set of brackets [@doi:10.7554/eLife.32822; @tag:deep-review; @isbn:9780262517638].
Manubot plugins provide easier, more convenient visualization of and navigation between citations [@doi:10.1371/journal.pcbi.1007128; @pmid:30718888; @pmcid:PMC6103790; @tag:deep-review].

Citation tags (i.e. aliases) can be defined in their own paragraphs using Markdown's reference link syntax:

[@tag:deep-review]: doi:10.1098/rsif.2017.0387

## Referencing figures, tables, equations

Figure @fig:square-image

Figure @fig:wide-image

Figure @fig:tall-image

Figure @fig:vector-image

Table @tbl:bowling-scores

Equation @eq:regular-equation

Equation @eq:long-equation

## Quotes and code

> Quoted text

> Quoted block of text
>
> Two roads diverged in a wood, and I—  
> I took the one less traveled by,  
> And that has made all the difference.

Code `in the middle` of normal text, aka `inline code`.

Code block with Python syntax highlighting:

```python
from manubot.cite.doi import expand_short_doi

def test_expand_short_doi():
    doi = expand_short_doi("10/c3bp")
    # a string too long to fit within page:
    assert doi == "10.25313/2524-2695-2018-3-vliyanie-enhansera-copia-i-insulyatora-gypsy-na-sintez-ernk-modifikatsii-hromatina-i-svyazyvanie-insulyatornyh-belkov-vtransfetsirovannyh-geneticheskih-konstruktsiyah"
```

Code block with no syntax highlighting:

```
Exporting HTML manuscript
Exporting DOCX manuscript
Exporting PDF manuscript
```

## Figures

![
**A square image at actual size and with a bottom caption.**
Loaded from the latest version of image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/square.png "Square image"){#fig:square-image}

![
**An image too wide to fit within page at full size.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/wide.png "Wide image"){#fig:wide-image}

![
**A tall image with a specified height.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/tall.png "Tall image"){#fig:tall-image height=3in}

![
**A vector `.svg` image loaded from GitHub.**
The parameter `sanitize=true` is necessary to properly load SVGs hosted via GitHub URLs.
White background specified to serve as a backdrop for transparent sections of the image.
](https://raw.githubusercontent.com/manubot/resources/master/test/vector.svg?sanitize=true "Vector image"){#fig:vector-image height=2.5in .white}

## Tables

| *Bowling Scores* | Jane          | John          | Alice         | Bob           |
|:-----------------|:-------------:|:-------------:|:-------------:|:-------------:|
| Game 1 | 150 | 187 | 210 | 105 |
| Game 2 |  98 | 202 | 197 | 102 |
| Game 3 | 123 | 180 | 238 | 134 |

Table: A table with a top caption and specified relative column widths.
{#tbl:bowling-scores}

|         | Digits 1-33                        | Digits 34-66                      | Digits 67-99                      | Ref.                                                        |
|:--------|:-----------------------------------|:----------------------------------|:----------------------------------|:------------------------------------------------------------|
| pi      | 3.14159265358979323846264338327950 | 288419716939937510582097494459230 | 781640628620899862803482534211706 | [`piday.org`](https://www.piday.org/million/)               |
| e       | 2.71828182845904523536028747135266 | 249775724709369995957496696762772 | 407663035354759457138217852516642 | [`nasa.gov`](https://apod.nasa.gov/htmltest/gifcity/e.2mil) |

Table: A table too wide to fit within page.
{#tbl:constant-digits}

|          | **Colors** <!-- $colspan="2" --> |                      |
|:--------:|:--------------------------------:|:--------------------:|
| **Size** | **Text Color**                   | **Background Color** |
| big      | blue                             | orange               |
| small    | black                            | white                |

Table: A table with merged cells using the `attributes` plugin.
{#tbl: merged-cells}

## Equations

A LaTeX equation:

$$\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}$$ {#eq:regular-equation}

An equation too long to fit within page:

$$x = a + b + c + d + e + f + g + h + i + j + k + l + m + n + o + p + q + r + s + t + u + v + w + x + y + z + 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9$$ {#eq:long-equation}

## Special

<i class="fas fa-exclamation-triangle"></i> [WARNING]{.semibold} _The following features are only supported and intended for `.html` and `.pdf` exports._
_Journals are not likely to support them, and they may not display correctly when converted to other formats such as `.docx`._

[Link styled as a button](https://manubot.org "Manubot Homepage"){.button}

Adding arbitrary HTML attributes to an element using Pandoc's attribute syntax:

::: {#some_id_1 .some_class style="background: #ad1457; color: white; margin-left: 40px;" title="a paragraph of text" data-color="white" disabled="true"}
Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
:::

Adding arbitrary HTML attributes to an element with the Manubot `attributes` plugin (more flexible than Pandoc's method in terms of which elements you can add attributes to):

Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
<!-- $id="element_id" class="some_class" $style="color: #ad1457; margin-left: 40px;" $disabled="true" $title="a paragraph of text" $data-color="red" -->

Available background colors for text, images, code, banners, etc:  

`white`{.white}
`lightgrey`{.lightgrey}
`grey`{.grey}
`darkgrey`{.darkgrey}
`black`{.black}
`lightred`{.lightred}
`lightyellow`{.lightyellow}
`lightgreen`{.lightgreen}
`lightblue`{.lightblue}
`lightpurple`{.lightpurple}
`red`{.red}
`orange`{.orange}
`yellow`{.yellow}
`green`{.green}
`blue`{.blue}
`purple`{.purple}

Using the [Font Awesome](https://fontawesome.com/) icon set:

<!-- include the Font Awesome library, per: https://fontawesome.com/start -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css">

<i class="fas fa-check"></i> <i class="fas fa-question"></i> <i class="fas fa-star"></i> <i class="fas fa-bell"></i> <i class="fas fa-times-circle"></i> <i class="fas fa-ellipsis-h"></i>

[
<i class="fas fa-scroll fa-lg"></i> **Light Grey Banner**<br>
useful for *general information* - [manubot.org](https://manubot.org/)
]{.banner .lightgrey}

[
<i class="fas fa-info-circle fa-lg"></i> **Blue Banner**<br>
useful for *important information* - [manubot.org](https://manubot.org/)
]{.banner .lightblue}

[
<i class="fas fa-ban fa-lg"></i> **Light Red Banner**<br>
useful for *warnings* - [manubot.org](https://manubot.org/)
]{.banner .lightred}


## Additional Content {.page_break_before}

This section just serves as a test.

\begin{equation}
\alpha = 42
\end{equation}

To get github-pages working, I just had to unselect and then reselect to use the branch gh-pages in the settings. This fortunately triggered the build of the webpage.

This sentence has been contributed by a collaborator.

[Nature article on collaborative writing](https://www.nature.com/articles/d41586-020-00916-6 "Synchronized editing: the future of collaborative writing")

[Article by TU Hamburg doing the same with gitlab](https://oa-pub.hos.tuhh.de/en/project/ "Modern Publishing: Digital Tools for Modern Publishing Processes")


## PyMotW - Manubot {.page_break_before}

[PLOS CB Paper](https://greenelab.github.io/meta-review/ "Open collaborative writing with Manubot")

[Manubot Website](https://manubot.org/catalog/)

[Manubot Github](https://github.com/manubot)

### Aims

- > disperse teams of collaborators
    - \> 10 authors

![](https://media.giphy.com/media/3ov9k5wE5YQjFPDfhe/giphy.gif)

![](https://media.giphy.com/media/xT9IgkY6M1SZd6spmE/giphy.gif)

- version control
    - transparency
    - better attribution of credit

- automatization
    - build
    - bibliography
    - deploying as webpage

### Motivation

- > traditionally publishing manuscripts based on
  - poprietary software (e.g. `.docx`) [^1]
  - offline tools (e.g. `Latex`)

[^1]: At least in the biology community

### Origin of Manubot

- open review @doi:10.1098/rsif.2017.0387
  - many authors bringing different expertise
  - hosted on Github
  - Creative Commons Attribution License ([CC BY 4.0](https://github.com/greenelab/deep-review/blob/master/LICENSE.md))
  - to support workflow $\rightarrow$ **manubot python package**

### Comparison to other writing platforms

[Comparison in Table 1](https://greenelab.github.io/meta-review/#tbl:platforms)

- thoughts
    - proposing changes really not possible in Overleaf?
    - characterlevel provenance really not possible in Overleaf?

- main competitor for manubot in our case: [Overleaf](https://www.overleaf.com/){.button}

### Workflow

[Illustration of Workflow](https://greenelab.github.io/meta-review/#fig:workflow)

### Features

#### manubot python packages

- > Process manuscript content to create outputs for Pandoc consumption.
  - I think it just moves things around and merges `.md` files
- citations [see USAGE.md](https://github.com/manubot/rootstock/blob/master/USAGE.md#citations)
  - [pandoc-manubot-cite](https://github.com/manubot/manubot#pandoc-filter)
  - cite-by-ID [Table with examples](https://greenelab.github.io/meta-review/#tbl:citations)

#### pandoc filters

- e.g. pandoc-xnos for referencing tables, equations (sections)

#### Pandoc Markdown

- citations
- table
- captions
- equations

#### html webpage

- themes $\rightarrow$ modify aesthetics
- interactive plots or mybinder
- [html plugins](https://github.com/essink/manubot_test/tree/master/build/plugins)
  - [hypothes.is](https://web.hypothes.is/) - annotations/comments
- hosted on github pages

#### Continuous Publication / Integration

- CI of your choice
- default Travis
- [Self-Hosted Github Actions Examples](https://github.com/essink/manubot_test/blob/master/.github/workflows/manubot.yaml)

#### [Timestamping](https://greenelab.github.io/meta-review/#timestamping)

### Limitations

- require *computational* background
- they advise having guidelines on contributions/authorship
  - e.g. 5 commits need to get the co-authorship
- primary output is html
  1. `.md` $\rightarrow$ `.html`
  2. `.html` $\rightarrow$ `.pdf`

- no Latex support yet!
  - of course formulae etc. work via MathJax, but no use of fancy packages (e.g. braket)
  - [Issue on Latex output](https://github.com/manubot/rootstock/issues/249)
  - working on `.md` $\rightarrow$ `.tex` via pandoc
    - issue is how to do this properly in CI

### How to set it up?

- [Manubot rootstock](https://github.com/manubot/rootstock)


## Personal Setup - Manubot {.page_break_before}

- manubot
  - Github Actions CI with self-hosted runner
    - use local conda environment
    - sync final `.pdf` to remarkable :P
- zotero
  - BibORB - brain.bib imported
  - collection for manubot manuscript
  - BetterBibtex for Zotero
    - automatized export of collection to `csl json` with correct key (`raw:<key>`) that is recognized by manubot
- Atom
  - packages
    - `markdown-preview-enhanced` for live preview
    - `language-pfm` for syntax highlighting (Pandoc Flavored Markdown)
    - `zotero-citation`
  - nice github integration
  - can use local builds
    - either `bash build/build.sh`
    - or `bash build/autobuild.sh` which triggers a run whenever a saved file shows changes $\rightarrow$ view complete document live in browser
- [mathpix](https://mathpix.com/)
  - snapshot formulae from photo/handwriting/papers and convert to latex
- whenever I start working with this great setup I end up improving the workflow and don't get anything done ...

![The sad truth...](https://imgs.xkcd.com/comics/automation.png )

![](https://imgs.xkcd.com/comics/is_it_worth_the_time.png )

![I definitely solved it...]( https://imgs.xkcd.com/comics/workaround.png)


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
