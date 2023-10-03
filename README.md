# Reveal-header Extension For Quarto customized for fbab
fork of https://github.com/shafayetShafee/reveal-header

## Install
> quarto add frederic-baucher/reveal-header

## Config - _quarto.yml
```yaml
title-slide-attributes:
    data-background-image: _extensions/frederic-baucher/reveal-header/resources/img/_template_first_slide.png
    data-background-size: contain
    data-background-opacity: "0.6"
format: 
  revealjs:
    hide-from-titleSlide: all # useless
    # top right (unless logo is empty => bottom right)
    slide-number: true
    # top middle and left
    sc-sb-title: true
    # top left (but not compatible with sc-sb-title)
    # header-logo: _extensions/frederic-baucher/reveal-header/resources/reveal_logo.svg
    # bottom - middle : repeat title
    footer: CASI - reveal-header example
    # bottom right
    logo: _extensions/frederic-baucher/reveal-header/resources/logo/gorilla.64x.png
    # bottom left
    # by default, shortcut to the menu
filters: 
  - reveal-header
slide-level: 3
```yaml

## Example

- The source code for another example that uses only `sc-sb-title`: [example_section-title.qmd](example_section-title.qmd) and the live demo of the rendered revealjs slides, [`example_section_title.html`](https://shafayetshafee.github.io/reveal-header/example_section_title.html)
