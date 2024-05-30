
La feuille de style `default.css` comprend les variables de la palette de couleur :

`:root` signifie que ces variables sont utilisées pour l'ensemble de la page.

--- code ---
---
language: html
filename: default.css
line_numbers: false
---

:root {
  --primary: #bccad0;
  --onprimary:#4f4e4e;
  --secondary: #495054;
  --onsecondary:#ffffff;
  --tertiary:#747474;
  --ontertiary: #ffffff;
  --page:#ffffff;
  --onpage:#000000;
  --detail: #9ba8ae;
  --detail2: #000000;
}

--- /code ---

Les variables de la palette de couleurs :

- `page` et `onpage` : couleurs contrastées utilisées pour l'arrière-plan de ta page.
- `primary`, `secondary`, et `tertiary` : ils peuvent être utilisés chaque fois que tu veux des éléments `<section>` ou `<div>` de couleurs différentes.
- `onprimary`, `onsecondary` et `ontertiary` : utilisés pour le texte afin de contraster avec les couleurs primaires, secondaires et tertiaires.
- `detail` et `detail2` : couleurs qui peuvent être utilisées pour ajouter des reflets colorés. `detail2` est utilisé pour le texte `<strong>` et les bordures.

Le schéma de couleurs `page` est utilisé en dehors du contenu `<main>`.
Le schéma de couleurs `primaire` est utilisé pour le contenu à l'intérieur de `<main>` à moins que tu n'utilises une classe différente.
