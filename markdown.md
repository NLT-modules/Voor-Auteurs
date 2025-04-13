# Markdown

Markdown is een eenvoudige opmaaktaal: platte tekst die *opgemaakt* wordt met kleine stukjes 'code'. Die tekst is vervolgens snel te exporteren naar allerlei andere formats zoals pdf, word, html etc.

## Indeling
| Kopjes | # H1 hoofdstuk <br> ## H2 sectie <br> ### H3 subsectie |  |

## Basic opmaak

| Element | Syntax | Voorbeeld | 
| --- | --- | --- |
| Bold | `**dik gedrukte tekst**` | **Bold** |
| Italic | `*italics*` | *Italics*
| Emphasis | `***emphasis***` | ***emphasis*** |
| in line Formule | `$F = m \cdot a$` | $F = m \cdot a$ |
| list | |
| new line | | | 

## Formules


## Admonitions

```{warning}
Hier een waarschuwing
```

tip / admonition / warning / note / objective / see also ...

## Opdrachten
```{exercise} Opdracht 1
:label: ex_opdr_1

Maak de som $4+2$
```

```{solution} ex_opdr_1
:class: dropdown

6
```



## Figuren
| Snelle figuur | `![](link naar figuur)` |

::::{tab-set}
:::{tab-item} Figuren

```{figure} https://github.com/rowanc1/pics/blob/main/sunset.png
:label: fig1
:width: 70%
:align: center

Met een mooi onderschrift
```

:::

:::{tab-item} MyST Syntax

````markdown
```{figure} https://github.com/rowanc1/pics/blob/main/sunset.png
:label: fig1
:width: 70%
:align: center

Met een mooi onderschrift
```
````

:::
::::

## YouTube

## Links
