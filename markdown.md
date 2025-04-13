# Markdown

Markdown is een eenvoudige opmaaktaal: platte tekst die *opgemaakt* wordt met kleine stukjes 'code'. Die tekst is vervolgens snel te exporteren naar allerlei andere formats zoals pdf, word, html etc.

## Indeling

```markdown
# H1 hoofdstuk  
## H1.1 sectie   
### H1.1.3 subsectie  
```

```{tip}
Nummer je hoofdstukken en sectie niet! Dit gebeurt automatisch.
```

Nieuwe regel krijg je door of een harde enter en een witregel of door twee spaties achter de zin.

## Basic opmaak

| Element | Syntax | Voorbeeld | 
| --- | --- | --- |
| Bold | `**dik gedrukte tekst**` | **Bold** |
| Italic | `*italics*` | *Italics*
| Emphasis | `***emphasis***` | ***emphasis*** |
| in line Formule | `$F = m \cdot a$` | $F = m \cdot a$ |


### Lijsten optie 1
::::{tab-set}
:::{tab-item} list
1. item 1
1. item 2.
1. item 3.
:::
:::{tab-item} syntax
```markdown
1. item 1
1. item 2.
1. item 3.
```
:::
::::

### Lijsten optie 2
::::{tab-set}
:::{tab-item} list
a. item 1
a. item 2.
a. item 3.
:::
:::{tab-item} syntax
```markdown
a. item 1
a. item 2.
a. item 3.
```
:::
::::

### Lijsten optie 3
::::{tab-set}
:::{tab-item} list
1. item 1
2. item 2.
3. item 3.
:::
:::{tab-item} syntax
```markdown
1. item 1
2. item 2.
3. item 3.
```
:::
::::



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

::::{tab-set}
:::{tab-item} YouTube
```{iframe} https://www.youtube.com/embed/YDBr1Lof_mI?si=thWYK9MFi5QJv-tW
:width: 80%
:align: center

Een superleuke video van het project [Show the Physics](https://interactivetextbooks.tudelft.nl/showthephysics)
```
:::
:::{tab-item} syntax
````markdown
```{iframe} https://www.youtube.com/embed/YDBr1Lof_mI?si=thWYK9MFi5QJv-tW
:width: 80%
:align: center

Een superleuke video van het project [Show the Physics](https://interactivetextbooks.tudelft.nl/showthephysics)
```
````
:::
::::

## Links
