# urbapadel.com — landing

Sitio estático de UrbaPadel (landing + legales). Sin dependencias, sin build.

## Contenido
- `index.html` — landing.
- `privacidad.html` — Política de Privacidad (mismo texto que la app).
- `terminos.html` — Términos y Condiciones.
- `img/` — capturas (ver `img/README.txt` para los nombres).
- `CNAME` — dominio propio (`urbapadel.com`).

## Publicar con GitHub Pages + dominio propio
1. Repo **público**.
2. Settings → Pages → Source: `Deploy from a branch` → rama `main`, carpeta `/ (root)`.
3. El `CNAME` ya fija `urbapadel.com`. En tu DNS (porkbun) apunta:
   - `urbapadel.com` (apex) → registros A de GitHub Pages:
     185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
   - `www` → CNAME a `davilarodri.github.io`
4. En Pages, marca **Enforce HTTPS** cuando GitHub emita el certificado.

URLs legales para las stores (una vez publicado):
- https://urbapadel.com/privacidad.html
- https://urbapadel.com/terminos.html

> Mientras propaga el DNS, la web está también en
> `https://davilarodri.github.io/urbapadelweb/`.
