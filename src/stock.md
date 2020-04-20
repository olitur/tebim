The Data Controller for SAS® enables users to self serve their data changes, and for data owners to retain control over those updates by reviewing and approving them.

<iframe src="https://player.vimeo.com/video/277472582" width="640" height="360" frameborder="0" allowfullscreen></iframe>



## Questionnaire BIM

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdiBj1LPPy7w4RXZHXaNQnu4wt5EGjH3tH1mVqmXlr0pOqIMg/viewform?embedded=true" width="640" height="1182" frameborder="0" marginheight="0" marginwidth="0">Chargement…</iframe>



## PDF

Vous pouvez y accéder là :  [TEBIM](/pdf/TEBIM.pdf){.new-tab}

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    src/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.



## Usage

In order to enable the theme just add one of the following lines to your
project's `mkdocs.yml`. If you installed Material using pip:

> :bulb: **Here is the full yml config used for these docs [mkdocs.yml](https://github.com/yakworks/mkdocs-material-components/blob/material-components-web/mkdocs.yml) :eyes:** provides a good starting point to get all the good extensions used here

``` yaml
theme: 'material-components'
```

If you cloned Material from GitHub:

``` yaml
theme_dir: 'mkdocs-material-components/material'
```

MkDocs includes a development server, so you can review your changes as you go.
The development server can be started with the following command:

``` sh
mkdocs serve
```

Now you can point your browser to [http://localhost:8000][9] and the Material
theme should be visible. From here on, you can start writing your documentation,
or read on and customize the theme through some options.

[9]: http://localhost:8000

## Options

The Material theme adds some extra variables for configuration via your
project's `mkdocs.yml`. See the following sections for all available options.

### Changing the color palette

A default hue is defined for every primary and accent color on Google's
Material Design [color palette][10], which makes it very easy to change the
overall look of the theme. Just set the primary and accent colors using the
following variables:

``` yaml
extra:
  palette:
    primary: 'indigo'
    accent: 'light blue'
```

Color names are case-insensitive, but must match the names of the Material
Design color palette. Valid values are: `red`, `pink`, `purple`, `deep purple`,
`indigo`, `blue`, `light blue`, `cyan`, `teal`, `green`, `light green`, `lime`,
`yellow`, `amber`, `orange`, `deep orange`, `brown`, `grey` and `blue grey`.
The last three colors can only be used as a primary color.

If the color is set via this configuration, an additional CSS file that
defines the color palette is automatically included. If you want to keep things
lean, clone the repository and recompile the theme with your custom colors set.
See the guide on [ckoi-lebim][11] for more information.

[10]: http://www.materialui.co/colors
[11]: ./howtos/ckoi-lebim.md


### links

[simple link](https://www.google.com )  
[with optional title](https://www.google.com "Google's Homepage")  
point to a [relative file or md](./notions/concepts-bim.md) or
mail link with emoji [📧](mailto:joshdev@9ci.com) or
click this cloud icon to see the list of icon options
[_cloud_{.icon}](https://material.io/icons/)


[Reference-Style Links][some reference id]
put link at bottom of paragraph or page.
you can use numbers or text for
[reference-style link definitions][1]  
or leave it empty and
just use the [link text itself]  

to [open in new tab](./howtos/avantages-bim.md){.new-tab}

to [avantages bim in new tab](./howtos/avantages-bim.md){target=blank}


use `{target=_blank} or {.new-tab}` attributes
use it on [ref links][new tab]{.new-tab} too






!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.





??? note "Phasellus posuere in sem ut cursus"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.



!!! abstract
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


!!! info
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


!!! tip
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


!!! success
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


!!! warning
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.



!!! danger
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


!!! example
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


### BetterEm

[BetterEm][6] improves the handling of emphasis markup (**bold** and *italic*)
within Markdown by providing a more sophisticated parser for better detecting
start and end tokens. Read the documentation for [usage notes][7].

  [6]: https://facelessuser.github.io/pymdown-extensions/extensions/betterem/
  [7]: https://facelessuser.github.io/pymdown-extensions/usage_notes/

### Caret

[Caret][8] makes it possible to highlight ^^inserted text^^. The portion of
text that should be marked as added must be enclosed in two carets `^^...^^`.

  [8]: https://facelessuser.github.io/pymdown-extensions/extensions/caret/

### Critic

[Critic][9] implements [Critic Markup][10], a Markdown extension that enables
the tracking of changes (additions, deletions and comments) on documents.
During compilation of the Markdown document, changes can be rendered (default),
accepted or rejected.

Text can be {--deleted--} and replacement text {++added++}. This can also be
combined into {~~one~>a single~~} operation. {==Highlighting==} is also
possible {>>and comments can be added inline<<}.

{==

Formatting can also be applied to blocks, by putting the opening and closing
tags on separate lines and adding new lines between the tags and the content.

==}

  [9]: https://facelessuser.github.io/pymdown-extensions/extensions/critic/
  [10]: http://criticmarkup.com/

### Details

[Details][11] adds [collapsible Admonition blocks][12] which can contain
arbitrary content using the HTML5 `details` and `summary` tags. Additionally,
all Admonition qualifiers can be used, e.g. `note`, `question`, `warning` etc.:

??? question "How many Prolog programmers does it take to change a lightbulb?"

    Yes.

  [11]: https://facelessuser.github.io/pymdown-extensions/extensions/details/
  [12]: ../admonition/#collapsible-blocks

### Emoji :tada:

[Emoji][13] adds the ability to insert, well, emojis! :smile:

By default, [Emoji][13] uses JoyPixles' emoji under the former name EmojiOne.
Recent versions of the extension lock support to an older version (2.2.7) due
to JoyPixels' newer, less permissible licenses included in later releases. This
restricts support to Unicode 9. To get the latest support for the current
Unicode version, you can use Twemoji instead which has a much more permissable
license. Simply override the default emoji index being used:

``` yaml
markdown_extensions:
  - pymdownx.emoji:
      emoji_index: !!python/name:pymdownx.emoji.twemoji
      emoji_generator: !!python/name:pymdownx.emoji.to_svg
```

To view all the available short names and emoji available, see
[Emoji's documentation][18] on your chosen index which includes links to the
files containing the short names and emoji associated with each supported
index.

!!! warning "Legal disclaimer"

    Material has no affiliation with [JoyPixles][15] or [Twemoji][14], both
    of which are licensed under [CC BY 4.0][16]. When including images or CSS
    from either provider, please read their licenses to ensure proper
    attribution: [EmojiOne][17] or [Twemoji][14].

### Icons :hatching_chick:

In addition, you can embed the Material Design icons, Fontawesome icons and
GitHub's Octicons directly from Markdown by using [Material for MkDocs's custom
emoji index][19]. It extends the Twemoji index with new short names that access
any of the included icons. To use the custom index, you need to use
`materialx.emoji` instead of `pymdownx.emoji`:

``` yaml
markdown_extensions:
  - pymdownx.emoji:
      emoji_index: !!python/name:materialx.emoji.material
      emoji_generator: !!python/name:materialx.emoji.to_svg
```

Example:

``` markdown
* :material-account-circle: – we can use Material Design icons
* :fontawesome-regular-laugh-wink: – we can also use FontAwesome icons
* :octicons-octoface: – that's not all, we can also use GitHub's Octicons
```

Result:

* :material-account-circle: – we can use [Material Design icons][20]
* :fontawesome-regular-laugh-wink: – we can also use [FontAwesome icons][21]
* :octicons-octoface: – that's not all, we can also use [GitHub's Octicons][22]

  [13]: https://facelessuser.github.io/pymdown-extensions/extensions/emoji/
  [14]: https://twemoji.twitter.com/
  [15]: https://www.joypixels.com/
  [16]: https://creativecommons.org/licenses/by/4.0/legalcode
  [17]: https://github.com/joypixels/emojione#emojione-version-2
  [18]: https://facelessuser.github.io/pymdown-extensions/extensions/emoji/#default-emoji-indexes
  [19]: https://github.com/facelessuser/mkdocs-material-extensions
  [20]: https://material.io/resources/icons/
  [21]: https://fontawesome.com/icons?d=gallery&m=free
  [22]: https://octicons.github.com/

### InlineHilite

[InlineHilite][23] adds support for inline code highlighting. It's useful for
short snippets included within body copy, e.g. `#!js var test = 0;` and can be
activated by prefixing inline code with a shebang and language identifier,
e.g. `#!js`.

  [23]: https://facelessuser.github.io/pymdown-extensions/extensions/inlinehilite/

### MagicLink

[MagicLink][24] detects links in Markdown and auto-generates the necessary
markup, so no special syntax is required. It auto-links `http[s]://` and
`ftp://` links, as well as references to email addresses.

  [24]: https://facelessuser.github.io/pymdown-extensions/extensions/magiclink/

### Mark

[Mark][25] adds the ability to ==highlight text== like it was marked with a
==text marker==. The portion of text that should be highlighted must be
enclosed in two equal signs `==...==`.

  [25]: https://facelessuser.github.io/pymdown-extensions/extensions/mark/

### SmartSymbols

[SmartSymbols][26] converts markup for special characters into their
corresponding symbols, e.g. arrows (<--, -->, <-->), trademark and copyright
symbols ((c), (tm), (r)) and fractions (1/2, 1/4, ...).
  
  
  [26]: https://facelessuser.github.io/pymdown-extensions/extensions/smartsymbols/


### Tabbed

[Tabbed][30] adds support for creating tabbed groups of Markdown content.

Example:

``` markdown
=== "Fruit List"
    - :apple: Apple
    - :banana: Banana
    - :kiwi: Kiwi

=== "Fruit Table"
    Fruit           | Color
    --------------- | -----
    :apple:  Apple  | Red
    :banana: Banana | Yellow
    :kiwi:   Kiwi   | Green
```

Result:

=== "Fruit List"
    - :apple: Apple
    - :banana: Banana
    - :kiwi: Kiwi

=== "Fruit Table"
    Fruit           | Color
    --------------- | -----
    :apple:  Apple  | Red
    :banana: Banana | Yellow
    :kiwi:   Kiwi   | Green

[30]: https://facelessuser.github.io/pymdown-extensions/extensions/tabbed/


Or this way :

The `mkdocs` executable is provided as an entry point and `serve` is the default
command. Start the development server in your project root – the folder where
`mkdocs.yml` resides — with:

=== "Unix"

    ```
    docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
    ```

=== "Windows"

    ```
    docker run --rm -it -p 8000:8000 -v "%cd%":/docs squidfunk/mkdocs-material
    ```



### Tasklist

[Tasklist][31] adds support for styled checkbox lists. This is useful for
keeping track of tasks and showing what has been done and has yet to be done.
Checkbox lists are like regular lists, but prefixed with `[ ]` for empty or
`[x]` for filled checkboxes.

Example:

``` markdown
* [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
* [x] Nulla lobortis egestas semper
* [x] Curabitur elit nibh, euismod et ullamcorper at, iaculis feugiat est
* [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [x] Sed egestas felis quis elit dapibus, ac aliquet turpis mattis
    * [ ] Praesent sed risus massa
* [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
* [ ] Nulla vel eros venenatis, imperdiet enim id, faucibus nisi
```


Résult :

* [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
* [x] Nulla lobortis egestas semper
* [x] Curabitur elit nibh, euismod et ullamcorper at, iaculis feugiat est
* [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [x] Sed egestas felis quis elit dapibus, ac aliquet turpis mattis
    * [ ] Praesent sed risus massa
* [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
* [ ] Nulla vel eros venenatis, imperdiet enim id, faucibus nisi




