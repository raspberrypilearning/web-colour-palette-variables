
Het `default.css` style sheet bevat een palet met kleurvariabelen:

`:root` betekent dat deze variabelen voor de hele pagina worden gebruikt.

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

De kleurenpalet variabelen:

- `page` and `onpage`: contrasterende kleuren die worden gebruikt voor de achtergrond van je pagina.
- `primary`, `secondary`, en `tertiary`: deze kunnen worden gebruikt wanneer je een andere kleur wilt voor `<section>` of `<div>` elementen.
- 'onprimary', 'onsecundary' en 'ontertiary': gebruikt voor tekst om te contrasteren met de primaire, secundaire en tertiaire kleuren.
- `detail` en `detail2`: kleuren die kunnen worden gebruikt om gekleurde accenten toe te voegen. `detail2` wordt gebruikt voor `<strong>` teksten en randen.

Het `page` kleurenschema wordt gebruikt buiten de `<main>` inhoud.
Het `primary` kleurenschema wordt gebruikt voor inhoud in `<main>` tenzij je een andere class gebruikt.
