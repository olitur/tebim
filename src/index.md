# Bienvenue sur le site d’information du BIM

Dernière mise à jour : {{ git_revision_date_localized }}


## Overview

The Data Controller for SAS® enables users to self serve their data changes, and for data owners to retain control over those updates by reviewing and approving them.

<iframe src="https://player.vimeo.com/video/277472582" width="640" height="360" frameborder="0" allowfullscreen></iframe>



## Questionnaire BIM

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdiBj1LPPy7w4RXZHXaNQnu4wt5EGjH3tH1mVqmXlr0pOqIMg/viewform?embedded=true" width="640" height="1182" frameborder="0" marginheight="0" marginwidth="0">Chargement…</iframe>



## PDF

Vous pouvez y accéder là :  [TEBIM](/pdf/TEBIM.pdf)

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


