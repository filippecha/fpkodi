# FP Kodi repozitář

Repozitář doplňků pro [Kodi](https://kodi.tv) (verze 19 Matrix a novější).
Doplňky nainstalované odsud se aktualizují automaticky.

| Doplněk | Popis |
|---|---|
| **Webshare Hledání** (`plugin.video.webshare.search`) | Vyhledávání a přehrávání videí z Webshare.cz, procházení filmů a seriálů s plakáty z TMDB |

## Instalace (jen jednou)

1. **Nastavení → Systém → Doplňky** → zapněte **Neznámé zdroje**.
2. **Nastavení → Správce souborů → Přidat zdroj** → **&lt;Žádný&gt;** a napište adresu
   `https://filippecha.github.io/fpkodi/`, jako název zadejte `fpkodi` → **OK**.
3. **Nastavení → Doplňky → Instalovat ze ZIP souboru** → `fpkodi` →
   `repository.fpkodi-….zip`.
4. **Instalovat z repozitáře** → **FP Kodi repozitář** → **Video doplňky** →
   **Webshare Hledání** → **Instalovat**.

Přihlášení k Webshare a TMDB API klíč se zadávají v nastavení doplňku.

## Pro vývojáře

Obsah repozitáře se generuje skriptem `tools/publish_repo.py` ze soukromého
zdrojového repozitáře; ručně ho neupravujte.

- `zips/addons.xml`, `zips/addons.xml.md5` – seznam doplňků pro Kodi
- `zips/<id>/<id>-<verze>.zip` – instalační balíčky
- `repository.fpkodi-<verze>.zip` + `index.html` – instalace repozitáře přes zdroj v Kodi
