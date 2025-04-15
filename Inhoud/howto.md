# Een snelle start
How to helpen bij het bekijken van het boek

1. Ga naar [Github.com](https://github.com/) en maak een account aan (als je dat nog niet hebt gedaan). Rechtsboven voor sign in / sign up.

```{figure} ../Figuren/signin.PNG
:width: 70%
```

2. Stuur Freek een berichtje met ofwel je mailadres waarmee je aangemeld hebt bij Github of je Github account naam. Je krijgt dan eerst toegang tot de sandbox zodat je vertrouwd kunt raken met de omgeving.

3. Accepteer de uitnodiging voor de repository die je ontvangt op je mail.

4. Bekijk het volgende filmpje:

```{iframe} https://www.youtube.com/embed/ewhBYkATbAc
:width:80%
```
5. Als je toegang hebt, kun je aan de slag met een eigen hoofdstuk maken. De repo waar je toegang toe krijgt vind je [hier](https://nlt-modules.github.io/Sandbox/).

6. Klik op *Add file* en *Create a new file*, zie hieronder.

```{figure} ../Figuren/newpage.png
:width: 70%
```

7. Geef je file een naam met als extensie *.md* bijv. *Freek.md*

```{figure} ../Figuren/naambestand.PNG
:width: 70%
```

8. In die file kun je jouw inhoud stoppen / ontwikkelen. 
9. Maak een hoofdstuk titel (# Mijn eerste titel) en een section titel (## Mijn eerste sectie). 
10. Druk op de groene *Commit changes* knop om je aanpassingen door te zetten naar de repo. Je kunt de commit een passende titel geven (of niet).

Wat er nu gebeurd is dat het boek opnieuw gemaakt wordt en via GitHub pages gepubliceerd. Na ongeveer 2 minuten kun je dus het resultaat op de website zien!


11. Hieronder weergegeven, de folderstructuur met de bestanden die je kunt aanpassen, rechtsboven de link naar het boek en hoe het er uit komt te zien.

```{figure} ../Figuren/howto.png
:width: 70%
```

12. Wil je iets doorvoeren op een specifieke pagina, bijvoorbeeld een figuur, mail Freek of klik op de <i class="fa-brands fa-github"></i> button bovenaan het scherm en open een issue door op de {fa}`lightbulb` button te klikken. Daar kun je commentaar voor die specifieke pagina kwijt.


13. Bekijk eens het [volgende hoofdstuk](markdown.md) voor wat je allemaal kunt toevoegen en pas dat aan in je eigen gemaakte hoofdstuk: klik daartoe op je gemaakte hoofdstuk en dan op het pennetje aan de rechterkant (*edit this file*)


14. En heb je de smaak te pakken? Volg onderstaande stappen om je eigen repository op te zetten!


```{note}
Goed om te weten... dit boek is gemaakt in [MyST](https://mystmd.org/guide) de meest recente versie van Jupyter Books.
```

## Eigen repository opzetten
Volg de volgende stappen om je eigen repository op te zetten. 

1. Ga naar deze [repository](https://github.com/TUD-SEEd/template.git)
2. Klik op de groene `use this template` en klik `create a new repository`.
3. Kies de naam voor je repository, en kies voor de optie `public`.
4. In je repository, klik links op pages en kies voor `Github actions`

``` {figure} ../Figuren/set_up_pages.png
:width: 80%
```

5. Klik op `code` en klik op het tandwiel (bij **About**) aan de rechterkant van het scherm. 
6. Vink **Use your GitHub Pages website** aan.
7. Ga naar actions in het bovenste menu, klik op de (rode) `inital commit` en klik op `re-run all jobs`

Het boek wordt nu nog een keer aangemaakt en ingeladen met GitHub pages. 

```{figure} ../Figuren/rerunjobs.PNG
---
name: fig_rerun
width: 70%
---
Als het boek bouw proces klaar is zijn alle bolletjes groen gekleurd.
```

8. Ga via de link (code, rechterkant onder **About**) naar de GitHub page waar het boek online gezet wordt.
9. De output is gelijk aan {numref}`Figuur {number} <fig_templatebook>` hieronder.

``` {figure} ../Figuren/templateboekoutput.PNG
---
name: fig_templatebook
width: 100%
---
De output van het boek zoals dat op GitHub pages staat.
```

```{tip}
Hulp nodig? Nodig FreekPols uit voor je repository zodat hij mee kan kijken!
```
