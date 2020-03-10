# MI-BHW

Ukoly na predmet MI-BHW

---

## Lab 2 a 3 -  DPA

Úkolem bylo naměřit data na osciloskopu a nahrát je do zvoleného softwaru a naprogramovat v něm DPA.\
Zvolila jsme software Mathematica.

V souboru `data.nb` jsou nahrány všechna data, která jsem naměřila pomocí osciloskopu. Tato data jsem pak ořezala podle pokynů a uložila do požadované matice. Toto by mělo být splněním druhého úkolu.

Pro třetí úkol jsem původní soubor s daty rozšířila o funkce, které by měly provést korelační DPA na naměřených datech. To je uloženo v souborech `analyzeDPA.nb` a `analyzeDPAcut.nb`. Tyto soubory se liší pouze v ořezání  načtených dat. \
Přestože program je napsán přesně podle zadání, nepodařilo se mi najít celý klíč správně. Čtyři byty nalezeného klíče se neshodují s použitým klíčem. U dvou z nich jsem zjistila, že správný klíč se najde hned jako 2. největší položka v korelační matici (místo 1., která je implicitně použita v daném cyklu). Zbylé dva byty klíče jsou v korelační matici přehlušeny šumem.

---
