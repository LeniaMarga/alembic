---
permalink: false
tags: boxLayout
---

**BoxLayout** is a primitive to show a container of other elements.
It has a uniform `padding` and transparent border.
The border-width is set to `--border-thin` and
does not set the `border-color`, that is up for consumers to specify.

This component concerns itself a little with colour.
It expects `--backgroundColor` and `--foreroundColor` to be set
and uses them to set the background and text colours respectively.
(These variables may be renamed soon).

| Attribute   | Type             | Default            | Info                                                |
| ----------- | ---------------- | ------------------ | --------------------------------------------------- |
| padding     | CSS padding      | var(--s1)          | How much empty space between the border and content |
| borderWidth | CSS border-width | var(--border-thin) | How much empty space between the border and content |
| invert      | boolean          | false              | Whether to swap the fore & background colour (WIP)  |