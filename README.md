# Cheat sheet RAS

## Koľko voľného priestoru (impresii) mám/e na nasadenie kampaní?
Voľné inventory si viete pozrieť priamo v DFP (google ad manager) pomocou **reportu**.   
- V karte **Reporting** sa preklikneme na [Reports](https://admanager.google.com/31040149#reports/report/list) kde klikneme na **New report** -               

![Image 1](https://imr.sk/ban/_img2020/_cheat_sheet/cheat-sheet-image-01.jpg)

- Nasledne si zvolime **Report type** na **_Future sell-through_** a potvrdime voľbu kliknutím na **Done** -

![Image 2](https://imr.sk/ban/_img2020/_cheat_sheet/cheat-sheet-image-02.jpg)

- Zadame **názov reportu** (je úplne jedno aký názov si zvolíte), **dátum** (_Dynamic_ - zadávame predvolené hodnoty / _Fixed_ - zadávame vlastné rozmedzie).  
V mojom prípade si chcem zistiť voľné impresie pre klienta Sportisimo na kampaň ktorá by mala bežať od 1.12. - 31.12.2020. (Nazov reportu - Sportisimo kampan 12/2020 / Timing) -

![Image 2](https://imr.sk/ban/_img2020/_cheat_sheet/cheat-sheet-image-03.jpg)

- Ďalej sa presunieme na možnosť **_Filters_**. Tu si vieme vyfiltrovať kde konkrétne ma kampaň bežať (_web / pozicia_). V mojom prípade si chcem zistiť voľné impresie pre plochu screen-top na aktualitach a športe. Vo filtry si vyhľadám možnosť **Ad unit (include child ad units)**, kde si vyhľadám plochu **screen - top** a z daných možností zaškrtnem aktuality - screen-top a šport screen-top. Voľbu potvrdím kliknutím na **Apply** -

![Image 2](https://imr.sk/ban/_img2020/_cheat_sheet/cheat-sheet-image-04.jpg)

- Nasledne si v karte **Dimensions** vyhľadáme **_Ad unit_** a tuto možnosť si zaklikneme. Potom v **Metrics** vyberieme obe možnosti ktoré chceme mať v reporte - **_Available impressions a Reserved impressions_** -

![Image 2](https://imr.sk/ban/_img2020/_cheat_sheet/cheat-sheet-image-05.jpg)

- Klikneme na **RUN** ak nechceme aby sa nám report uložil, alebo na **SAVE AND RUN** ak chceme mať report uložený a prístupný.

- V mojom prípade vyzerý report nasledovne. Z reportu si vieme vypočítať voľný priestor pre nasadenie kampaní. Napríklad pre plochu **screen-top na aktualitach** vieme, že **celkový voľný priestor** na dané obdobie je _10 515 875_ imp a z toho **už rezervovaných imp** je _5 866 300_. Z tohto si vieme vypočítať že momentálny voľný priestor je _4 649 475_ (available impressions - reserved impressions).   
  - **POZOR!**, síce sme si vypočítali že máme niečo cez 4,5 miliona voľných impresií. **ALE** report nepočíta s cappingom. Takže je potrebné rátať s bežne používaným cappingom na jednú kampaň - 3/lifetime + 1/day. To znamená že realne využiteľný priestor pre moju kampaň, ktorý môžem navrhnúť klientovi je cca **800 000 imp** ( 4,5m / 3 ), pretože treba rátať s nejakou rezervou a odchylkou systému.   
  - **POZOR!** nevieme si tu vyklikať a pridať cielenie na vek a pod... Jedine si vo filtroch vieme pridať Audience segmenty (behavioralne cielenie).