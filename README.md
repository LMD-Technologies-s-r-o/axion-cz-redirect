# axion-cad.cz – jen přesměrování
Česká verze webu se přesunula na **https://axion-cad.com/cs/**. Toto repo obsahuje jen přesměrovací stránky
(staré adresy `/`, `/funkce/`, `/propojeni/`, `/z-praxe/`, `/nasazeni/` → `axion-cad.com/cs/...`, ostatní cesty přes `404.html`).
**Generované – needitovat ručně.** Vytváří se v repu `axion-web` příkazem `python3 tools/build.py ../axion-cz-redirect`.
`CNAME` (`axion-cad.cz`) neměnit, dokud doména nepřejde na trvalé přesměrování 301 (Cloudflare).
