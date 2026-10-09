MONI. – první funkční verze PWA

JAK SPUSTIT:
1. Rozbal ZIP. Nahraj OBSAH složky moni-app (index.html, app.js, style.css, icon.png, mark.png, manifest.webmanifest, sw.js) do kořenového adresáře webového hostingu (např. GitHub Pages).
2. Otevři HTTPS adresu webu na iPhonu v Safari.
3. Sdílet → Přidat na plochu.

Pro místní test na počítači lze ve složce spustit: python -m http.server 8000
Potom otevřít http://localhost:8000

Data se ukládají lokálně v prohlížeči (localStorage), bez účtu a bez synchronizace. Doporučujeme exportovat zálohy v Nastavení.

Funkce: první spuštění, počáteční stavy, vlastní kategorie, příjem/výdaj, převod, vratka, blokace, historie, úpravy, smazání, statistiky, export/import JSON.

Poznámka: bez bankovního propojení je stav blokací zadáván ručně. Vratka je samostatný typ pohybu a snižuje čisté výdaje měsíce, nikoli konkrétní kategorii. Výchozí kategorie Úspory je pouze volitelná kategorie výdaje; pro přesuny vlastních úspor používej Převod.
