---
Title: LOAD
Description: This is our colors page.
Template: rapp
---

# Rapport om load

Jag kommer att analysera olika laddings tider på tre olika webbplatser. Som bidrar till hur högt de blir rankade på tex google.

Urval
-----------------------

De tre webbplatser jag har valt att analysera är Webbhallen.com, Inet.se och Elgiganten.se. Valet av dessa webbplatser grundar sig på att de tillhör samma kategori.

Metod
-----------------------

Den metod jag använde innefattade Googles verktyg PageSpeed för att analysera följande parametrar: LPC, INP, CLS, FCP, TTFB, prestanda, tillgänglighet, bästa metoder samt SEO. Därefter använde jag webbläsarens inspektionsverktyg för att identifiera laddningstider och tiden för DOMContentLoaded.

Resultat
-----------------------

<div class="kalk">
   <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQZhx_zqOY0SUhdvB00BYTSUyo3LfqeybS5kDUDYu3AucihLU7Gt7FOkrh4OorhzDB044-ndJ4N_siy/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

Webbhallen:
-----------------------

![webbsite](%assets_url%/img/webbhallen.png){.webbsite}
<div class="links">
    <ul>
        <li><a href="https://www.webhallen.com" target="_blank">Hem</a></li>
        <p>LPC: 1s | 1s</p>
        <p>INP: 170ms | 115ms</p>
        <p>CLS: 0.71 | 0.31</p>
        <p>FCP: 0.9s | 0.8s</p>
        <p>TTFB: 0.4s | 0.3s</p>
        <p>Prestanda: 92 | 100</p>
        <p>Tillgänglighet: 95 | 96</p>
        <p>Bästa metoder: 96 | 96</p>
        <p>SEO: 92 | 92</p>
        <p>Load: 841ms</p>
        <p>DOMCL: 634ms</p>
        <li><a href="https://www.webhallen.com/se/category/16421-Gaming-PC" target="_blank">Gaming-Pc</a></li>
        <p>LPC: 2.1s | 1s</p>
        <p>INP: 148ms | 104ms</p>
        <p>CLS: 0.65 | 0.3</p>
        <p>FCP: 1s | 0.8s</p>
        <p>TTFB: 0.4s | 0.3s</p>
        <p>Prestanda: 88 | 98</p>
        <p>Tillgänglighet: 81 | 83</p>
        <p>Bästa metoder: 96 | 96</p>
        <p>SEO: 54 | 54</p>
        <p>Load: 923ms</p>
        <p>DOMCL: 770ms</p>
        <li><a href="https://www.webhallen.com/se/product/369945-Webhallen-Config-Ultra-R9-7950X3D-RTX-4090" target="_blank">Pc</a></li>
        <p>LPC: 2.9ms | 1s</p>
        <p>INP: 117ms | 83ms</p>
        <p>CLS: 0.16 | 0.12</p>
        <p>FCP: 1.1ms | 0.8s</p>
        <p>TTFB: 0.5ms | 0.3s</p>
        <p>Prestanda: 94 | 99</p>
        <p>Tillgänglighet: 90 | 91</p>
        <p>Bästa metoder: 96 | 96</p>
        <p>SEO: 85 | 85</p>
        <p>Load: 955ms</p>
        <p>DOMCL: 616ms</p>
    </ul>
    <h3>Förbättring</h3>
    <p>Förbättra sin Cumulative Layout Shift: En förbättring av CLS minskar oväntade layoutförändringar på en webbplats, vilket förbättrar användarupplevelsen genom att förhindra frustration och felklick. Det bidrar även till snabbare upplevd laddningstid, bättre synlighet i sökmotorer genom Google Core Web Vitals, samt ökad användarinteraktion och konvertering.</p>
</div>

Inet:
-----------------------

![webbsite](%assets_url%/img/inet.png){.webbsite}
<div class="links">
    <ul>
        <li><a href="https://www.inet.se" target="_blank">Hem</a></li>
        <p>LPC: 0.9s | 0.6s</p>
        <p>INP: 80ms | 23ms</p>
        <p>CLS: 0.05 | 0</p>
        <p>FCP: 0.6s | 0.5s</p>
        <p>TTFB: 0.3s | 0.2s</p>
        <p>Prestanda: 75 | 94</p>
        <p>Tillgänglighet: 100 | 93</p>
        <p>Bästa metoder: 100 | 100</p>
        <p>SEO: 100 | 100</p>
        <p>Load: 1.1s</p>
        <p>DOMCL: 377ms</p>
        <li><a href="https://www.inet.se/kategori/31/datorkomponenter" target="_blank">Datorkomponenter</a></li>
        <p>LPC: 0.5s | 0.4s</p>
        <p>INP: 61ms | 6ms</p>
        <p>CLS: 0.04 | 0</p>
        <p>FCP: 0.4s | 0.4s</p>
        <p>TTFB: 0.3s | 0.2s</p>
        <p>Prestanda: 95 | 98</p>
        <p>Tillgänglighet: 96 | 91</p>
        <p>Bästa metoder: 100 | 100</p>
        <p>SEO: 100 | 100</p>
        <p>Load: 1.43s</p>
        <p>DOMCL: 414ms</p>
        <li><a href="https://www.inet.se/produkt/5414012/asus-geforce-rtx-4070-ti-super-16gb-rog-strix-gaming-oc" target="_blank">Grafikkort</a></li>
        <p>LPC: 0.7s | 0.7s</p>
        <p>INP: - | -</p>
        <p>CLS: 0.05 | 0</p>
        <p>FCP: 0.6s | 0.6s</p>
        <p>TTFB: 0.4s | 0.4s</p>
        <p>Prestanda: 74 | 94</p>
        <p>Tillgänglighet: 90 | 90</p>
        <p>Bästa metoder: 100 | 100</p>
        <p>SEO: 85 | 85</p>
        <p>Load: 1.22ms</p>
        <p>DOMCL: 507ms</p>
    </ul>
    <h3>Förbättring</h3>
    <p>Inet har väldigt bra resultat men. En förbättring av en hemsidan innebär att minska laddningstiden, vilket förbättrar användarupplevelsen, ökar sidans prestanda och kan bidra till bättre placering i sökmotorernas resultat.</p>
</div>

Elgiganten:
-----------------------

![webbsite](%assets_url%/img/elgiganten.png){.webbsite}
<div class="links">
    <ul>
        <li><a href="https://www.elgiganten.se" target="_blank">Hem</a></li>
        <p>LPC: 1.1s | 0.9s</p>
        <p>INP: 185ms | 93ms</p>
        <p>CLS: 0.09 | 0.04</p>
        <p>FCP: 1s | 0.8s</p>
        <p>TTFB: 0.5s | 0.4s</p>
        <p>Prestanda: 56 | 61</p>
        <p>Tillgänglighet: 84 | 84</p>
        <p>Bästa metoder: 93 | 74</p>
        <p>SEO: 85 | 85</p>
        <p>Load: 2.79s</p>
        <p>DOMCL: 814ms</p>
        <li><a href="https://www.elgiganten.se/datorer-kontor/datorer" target="_blank">Dator kategori</a></li>
        <p>LPC: 1.3s | 1.4s</p>
        <p>INP: 280ms | 186ms</p>
        <p>CLS: 0.07 | 0.04</p>
        <p>FCP: 0.9s | 0.9s</p>
        <p>TTFB: 0.4s | 0.4s</p>
        <p>Prestanda: 29 | 54</p>
        <p>Tillgänglighet: 81 | 85</p>
        <p>Bästa metoder: 75 | 93</p>
        <p>SEO: 85 | 85</p>
        <p>Load: 4.33s</p>
        <p>DOMCL: 1.86s</p>
        <li><a href="https://www.elgiganten.se/product/gaming/gaming-pc/stationar-gamingdator/pcspecialist-core-230-i5-12f1610244060ti-stationar-gamingdator/694242" target="_blank">Dator</a></li>
        <p>LPC: 1.1s | 0.8s</p>
        <p>INP: 191ms | 124ms</p>
        <p>CLS: 0.07 | 0.04</p>
        <p>FCP: 1s | 0.7s</p>
        <p>TTFB: 0.5s | 0.4s</p>
        <p>Prestanda: 51 | 60</p>
        <p>Tillgänglighet: 82 | 92</p>
        <p>Bästa metoder: 71 | 70</p>
        <p>SEO: 85 | 85</p>
        <p>Load: 4s</p>
        <p>DOMCL: 1.5s</p>
    </ul>
    <h3>Förbättring</h3>
    <p>En förbättring av en hemsida innebär att minska laddningstiden och optimera prestanda, tillgänglighet, bästa metoder och SEO, vilket leder till en bättre användarupplevelse och högre sökmotorrankning.</p>
</div>

Topplista:
-----------------------

1. Inet - Väldigt snabbb och användar vänlig
2. Webbhallen - Snabbb och användar vänlig
3. Elgiganten - Relativt snabbb och små brister i användar vänlighet

Analys
-----------------------

Resultaten visar en tydlig variation i prestanda, tillgänglighet och laddningstider mellan olika webbplatser och enheter (mobil och dator). Elgiganten presterar generellt bättre på dator än mobil, med lägre LPC, INP, och CLS samt kortare laddningstider. Däremot visar Elgiganten DK och Elgiganten D högre LPC och längre laddningstider, särskilt på mobila enheter.

Webbhallen uppnår utmärkta resultat för dator, med höga värden för Prestanda, Tillgänglighet, och Bästa metoder, men presterar något sämre på mobil, särskilt med högre CLS och längre Load-tider. Liknande trender syns för Wh GPC och Wh PC, där dator presterar bäst i samtliga mätpunkter.

Inet och dess variationer visar överlag stabila resultat, med låga LPC, INP och CLS, samt korta laddningstider på både mobil och dator. Prestanda- och SEO-resultaten är konsekvent höga, med Bästa metoder på maximala 100 för samtliga mätningar.

Sammanfattningsvis är prestanda och laddningstider generellt bättre på dator än mobil, vilket tyder på att mobila versioner av webbplatserna behöver ytterligare optimering, särskilt avseende LPC, CLS och laddningstid. Detta är avgörande för att förbättra användarupplevelse och rankning i sökmotorer.

Referenser
-----------------------

<div class="links">
    <ul>
        <li><a href="https://www.webhallen.com" target="_blank">Webhallen</a></li>
        <li><a href="https://www.inet.se" target="_blank">Inet</a></li>
        <li><a href="https://www.elgiganten.se" target="_blank">Elgiganten</a></li>
    </ul>
</div>

Övrigt
-----------------------

Jag skrev detta själv.