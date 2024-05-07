
The `default.css` style sheet includes a palette of colour variables:

`:root` means that these variables are used for the whole page. 

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

The colour palette variables:
+ `page` and `onpage`: contrasting colours used for the background of your page.
+ `primary`, `secondary`, and `tertiary`: these can be used whenever you want different coloured `<section>` or `<div>` elements.
+ `onprimary`, `onsecondary`, and `ontertiary`: used for text to contrast with the primary, secondary, and tertiary colours.
+ `detail` and `detail2`: colours that can be used to add coloured highlights. `detail2` is used for `<strong>` text and borders. 

The `page` colour scheme is used outside of the `<main>` content. 
The `primary` colour scheme is used for content inside `<main>` unless you use a different class. 
