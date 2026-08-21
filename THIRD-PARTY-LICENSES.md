# Third-party licenses

Every page on this site is built with `embed-resources`, so it is one self-contained file: the stylesheets, the scripts and the typefaces are not fetched from anywhere, they are inlined into the page itself. That is deliberate --- a deck opens in a lecture hall with no wifi --- and it means each page *redistributes* the software and fonts below rather than merely linking to them. Several of those licences require their notice to travel with the copy. This file is that notice.

It is generated material's companion, not a claim of ownership: nothing listed here belongs to the course. The course's own licence is in [LICENSE.md](LICENSE.md).

## Fonts

Both are embedded as base64 WOFF2 inside the pages' stylesheets, in the weights the site actually uses. Both are under the [SIL Open Font License, Version 1.1](https://openfontlicense.org/), which permits this and asks that the copyright notice and licence be retained wherever the font is redistributed.

**Source Sans 3** --- the course website and the landing page.

> Copyright 2010-2020 Adobe (http://www.adobe.com/), with Reserved Font Name 'Source'.
> All Rights Reserved. Source is a trademark of Adobe in the United States and/or other countries.
>
> This Font Software is licensed under the SIL Open Font License, Version 1.1.

**Nunito** --- the slide decks, in both the presentation and the reading page.

> Copyright 2014 The Nunito Project Authors (https://github.com/googlefonts/nunito)
>
> This Font Software is licensed under the SIL Open Font License, Version 1.1.

The full licence text is at <https://openfontlicense.org/open-font-license-official-text/>. Note the one restriction that matters in practice: neither font may be sold on its own, and neither may be redistributed under a name containing a Reserved Font Name. Shipping them inside a web page, as here, is expressly permitted.

## Software

**reveal.js 5.1.0** --- the slide decks. MIT License, Copyright (c) 2011-2024 Hakim El Hattab, https://hakim.se, and reveal.js contributors. <https://github.com/hakimel/reveal.js>

**Bootstrap** --- the landing page and the notebooks, through Quarto's cosmo theme. MIT License, Copyright (c) 2011-2024 The Bootstrap Authors. <https://github.com/twbs/bootstrap>

**Quarto** --- the site is rendered by Quarto, which inlines several small components of its own into each page, among them AnchorJS (MIT), Tippy.js and Popper (MIT), and clipboard.js (MIT). Quarto itself is MIT-licensed. <https://github.com/quarto-dev/quarto-cli>

**MathJax** --- loaded by the decks for mathematical notation. Apache License 2.0. <https://github.com/mathjax/MathJax>

Each of these is MIT or Apache 2.0, both of which permit redistribution in source and binary form provided the copyright notice and permission notice are included --- which is what this file does. The full text of the MIT License is at <https://opensource.org/license/mit>, and of Apache 2.0 at <https://www.apache.org/licenses/LICENSE-2.0>.

## Material quoted inside the course

The slide decks reproduce a tweet, and screenshots of the Overleaf, MATLAB and Jupyter interfaces. These belong to their owners and appear as quotation for teaching. They are not covered by the course's licence and are not offered for reuse.
