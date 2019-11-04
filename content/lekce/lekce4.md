---
title: "Lekce 4 - Pozicování a layout"
date: "2019-10-21"
publishDate: "2019-01-01"
tags: [html, css, layout]
---

- [Materiály](/materialy/lekce4/lekce4.zip)
- [Prezentace](/prezentace/prezentace4.html)
- [4 minute design](https://jgthms.com/web-design-in-4-minutes)
- [Videozáznam](https://youtu.be/v0jcmvjy9AE)

## Domácí úkol

> [Možné řešení úkolu](/materialy/lekce4/ukol_lekce4-reseni.zip)

* Tentokrát to uděláme trošku jinak
* Budeme vycházet z [tohoto dokumentu](/materialy/lekce4/ukol_lekce4.zip)
- Celý obsah je obalený v `<div class="profil">` – nastavím šířku
- Uvnitř `<div class="hlavicka">` ve které je obrázek fotky a ikony
    - Ikonka je bílá, stačí nastavit barvu pozadí a kulaté rohy (`border-radius`)
    - Ikonku lze napozicovat pomocí `position: absolute` uvnitř rodiče, který má `position: relative`
    - Fotce omezit šířku aby se přizpůsobila rodiči (`width: 100%`)
* Váš výsledek by měl vypadat takto

![](/materialy/lekce4/zadani-ukolu.jpg)
