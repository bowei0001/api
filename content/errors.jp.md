---
weight: 20
title: エラー

---

# エラー

<aside class="notice">(TODO日本語）This error section is stored in a separate file, errors.md. DocuAPI allows you to split the single page documentation in as many files as needed. Files are included in the  default Hugo page order . One way of ordering the pages is by setting the page `weight` in the front matter. Pages with lower weight will be listed first.</aside>

Kittn-APIet tek i bruk følgjande feilkodar:

Feilkode | Forklaring
---------- | -------
400 | Bad Request -- Din førespurnad har forbetringspotensiale
401 | Unauthorized -- Feil API-nøkkel
403 | Forbidden -- Denne kattungen er berre tilgjengeleg for administratorar
404 | Not Found -- Denne kattungen vart ikkje funnen
405 | Method Not Allowed -- Du prøvde å få tak i kattungen på ein snodig og ulovleg måte
406 | Not Acceptable -- Du bad om eit format som ikkje er  JSON
410 | Gone -- Kattungen har rømt frå serveren.
418 | I'm a teapot
429 | Too Many Requests -- Du spør om for mange kattungar, ta det med ro!
500 | Internal Server Error -- Me har eit problem med serveren. Prøv igjen seinare.
503 | Service Unavailable -- Me er nede for vedlikehald. Prøv igjen seinare.

