# Technische introductie

```{warning}
Laat je niet door onderstaande afschrikken. Het geeft een technisch inhoudelijk overzicht van wat er hier precies gebeurt. Je kunt ook meteen door met [de snelle start](howto.md)
```

Online / digitale modules, zoals deze [schakelmodule](https://nlt-modules.github.io/Schakelmodule/) kun je maken met behulp van [MyST](https://mystmd.org) (de opvolger van [Jupyter Book](https://jupyterbook.org)). MyST is een krachtig auteursframework dat het maken van (online) blogs, boeken, artikelen en tijdschriften ondersteunt. 

Voor de online boeken maken we gebruik van een online beheerplatform genaamd [GitHub](https://github.org). Een klein stukje software is al toegevoegd die automatisch bij elke wijziging de bronbestanden omzet in een online boek. Je kunt, zonder installeren van enig software direct online aan de slag!

Het beheer van alle NLT modules gebeurt met behulp van een [organization in GitHub](https://github.com/NLT-modules) zodat er altijd technische ondersteuning mogelijk is. De eigenaar van de organization kan toegang verlenen tot specifieke repositories. 

In veel gevallen is het toch fijn om offline ook aan het boek te kunnen werken. Daartoe raden we Visual Studio Code aan.

Hieronder volgt een meer gedetailleerde uitleg.

## MyST

[MyST](https://mystmd.org) is een open-source tool waarmee je zowel wetenschappelijke artikelen alsook boeken kunt maken die via GitHub (of een server) gehost kunnen worden. Er is een uitgebreide community die MyST helpt te ontwikkelen. Er is ook een [uitgebreide handleiding](https://mystmd.org/guide/) beschikbaar om je op weg te helpen (maar dat doen we hier ook).

## Github

[GitHub](http://github.com) is een webplatform voor versiebeheer en samenwerking bij softwareontwikkeling. Het stelt ontwikkelaars in staat om overal ter wereld samen te werken aan projecten door wijzigingen bij te houden en te beheren. Ook gebruikers van Jupyter Books kunnen input leveren door bijvoorbeeld een issue aan te maken (zie de button rechtsboven). 

```{iframe} https://www.youtube.com/embed/bF3lkiZ8Arc?si=CDdZ4QShvKyfNq2i
:width: 80%
```

Meerdere auteurs kunnen tegelijk aan eenzelfde module werken. Als je online werkt, dan gaat dat vrijwel altijd goed. Werk je ook offline, dan moet je zorgen dat je altijd offline materiaal eerst synchroniseert (pull) met wat online staan en als je klaar bent andersom (push). 

Voor een verdere introductie tot GitHub, bekijk dit filmpje:

```{iframe} https://www.youtube.com/embed/iv8rSLsi1xo?si=_DkJP2MBTRLK8fIM
:width: 80%
```

Er zijn ook [online lessen](https://swcarpentry.github.io/git-novice/) beschikbaar rond het gebruik van GitHub.

Weet je zeker dat je aan de slag gaat? Voer dan de volgende stappen uit:
- [] Ga naar [GitHub](http://github.com)
- [] Maak een account aan.
- [] Lees de [snelle start](howto.md)

### Organizations
Er is een [NLT organization](https://github.com/NLT-modules) aangemaakt in Github. Daarin kunnen alle modules komen te staan. Het voordeel van zo'n organization is dat er experts ondersteuning kunnen bieden wanneer het niet lukt.

Ben je nog niet bekend tot het werken in GitHub en het maken van een Jupyter boek? Vraag toegang tot de [sandbox](https://github.com/NLT-modules/Sandbox).

### Rollen
Zowel op het niveau van de organization als op het niveau van een repository kunnen [verschillende rollen](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization) toegekend worden. Zo heeft de beheerder de rechten om de module te *vernietigen*, kun je iemand de rol toewijzen om alleen mee te lezen, of bijvoorbeeld ook problemen te rapporteren of direct zelf aan te passen.

(githubdesktop)=
### Github Desktop
GitHub Desktop is een grafische gebruikersinterface (GUI) om (eenvoudiger) te werken met GitHub. Om de GUI te installeren en in te stellen:

* Download [git](https://git-scm.com/downloads)
* Download het [installatieprogramma](https://github.com/apps/desktop) en installeer het met de standaardinstellingen. Als het de eerste keer niet werkt, probeer het installatieprogramma dan opnieuw uit te voeren.
* Wanneer je de GUI voor het eerst opent, word je gevraagd om je aan te melden bij je GitHub-account. Voer je gegevens in.
* Dat is alles, je bent nu klaar om de GUI te gebruiken!
* Verdere documentatie over de installatie en instellingen vind je [hier](https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop).

```{note}
Werk je met TUD Gitlab, dan is een net andere aanpak nodig, zie de [beschrijving van de collega's](https://mude.citg.tudelft.nl/2023/software/git_install/).
```

## VSC

Visual Studio Code (VSC) is een populaire code-editor ontwikkeld door Microsoft. Het biedt ondersteuning voor meerdere programmeertalen en heeft uitgebreide functionaliteiten zoals debugging, versiebeheer (werkt goed samen met bijv. [github](./Github.md)) en extensies.

``` {figure} ../Figuren/VSC_ps.PNG
---
name: VSV_ps
width: 70%
---
VSC voor het maken van je boek, geheel links het menu, daarnaast de folders met de bestanden. Centraal de opmaaktaal en rechts een preview van boek.
```

```{exercise}
[Download](https://code.visualstudio.com/Download) en installeer VSC.
```

## Extensies
Een aantal extensies zijn handig / nodig voor programmeren in Python en/of het maken van een Jupyter Boek.
- [MyST-Markdown](https://marketplace.visualstudio.com/items?itemName=ExecutableBookProject.myst-highlight) - adds support for MyST markdown, including previews.
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) - Extensie voor Jupyter 
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - for obvious reasons. Also includes Jupyter Notebook rendering.
- [Spell checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - Spelling checker for source code and text
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) - Your AI pair progammer
- [Jupyter Cell Tags](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-jupyter-cell-tags) - Jupyter Cell Tags support


````{exercise}
Installeer de extensie Jupyter, MyST-Markdown, Python & Code Spell checker, zie {numref}`Figuur {number} <fig_extensions>` waar deze te vinden zijn.

``` {figure} ../Figuren/extensions.PNG
---
name: fig_extensions
width: 70%
---
Installeer de extensie Jupyter, MyST-Markdown, Python & Code Spell checker.
```
````
