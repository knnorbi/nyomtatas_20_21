# Nyomtatás

Nyissa meg a *nyomtatas.html* állományt és szerkessze annak tartalmát az alábbiak szerint:

1. A weboldal karakterkódolása utf-8, nyelve magyar, a böngésző címsorában megjelenő címe *„Nyomtatás”* legyen!
2. A weboldal fejrészében helyezzen el hivatkozást a *nyomtatas.css* stíluslapra, valamint a *nyomtatas.js* állományra a meglévő azonos típusú hivatkozások után!
3. A weboldalon keresse meg *Johannes Gutenberg, Alois Senefelder és William Henry Fox Talbot* nevét, majd alakítsa a nevek szövegét hivatkozássá! Kattintásra a hivatkozott weboldal új ablakban/böngészőfülön nyíljon meg. A fenti személyek munkásságát bemutató céloldalak URL címeit a *webforras.txt* szöveges állományban találja!
4. Helyezze el a minta szerinti helyeken egy-egy új bekezdésben a *kezi_szedes.jpg, az ofszet_nyomogep.jpg és a nyomdagep_pultja.jpg* állományokat! A képekhez tartozó feliratokat (a böngészőben ezek jelenjenek meg, ha fölé visszük az egérkurzort, vagy ha a kép nem tölthető be) illessze be a webforras.txt szöveges állományból! A beillesztett képeket formázza a Bootstrap *img-thumbnail* osztálykijelölőinek használatával.
5. A weboldalon készítsen egy újabb tartalmi blokkot az alábbi leírás és a minta alapján:

  - Az új tartalmi blokk a Bootstrap rács második sorában, a *„Digitális eljárások”* blokkja után helyezkedjen el! A sor blokkjainak (oszlopainak) szélességét a korábbi 6:6 helyett 4:4:4 arányban ossza el!
  - A blokkba illessze be a *webforras.txt* szöveges állomány megfelelő részét! Alakítsa ki a minta szerinti 3-as szintű címsort és a felsorolást!
  - A beillesztett űrlapban a méret megadására szolgáló mezők típusát módosítsa szám típusúra! A méret mezők alapértelmezett értékei az A3-as lapméretnek megfelelően 297 (szélesség) és 420 (magasság) legyenek!
  - A papírtípus választását segítő lenyíló lista kódját egészítse ki, hogy a *„Matt, vastag, általános papír (120 g/m2)”* opció legyen az alapértelmezett!
  - A *kalkulalGomb* azonosítójú gomb űrlapelem kattintás eseményéhez rendelje a *kalkulal()* függvényhívást!
  - A gomb utáni keret elrejtéséhez formázza azt a *valasz* azonosítókijelölővel! Tanulmányozza a keret tartalmát, a megjelenítendő adatokat e szövegkörnyezetben kell majd elhelyeznie!

6. Nyissa meg a *nyomtatas.css* állományt, módosítsa a következők szerint:

  - A *bg-fej* osztályba sorolt elemek háttérképe a drukletters.jpg kép legyen!
  - A szélesség és magasság mezők margóját állítsa be úgy, hogy fent 0px legyen, vízszintesen középre kerüljenek, alattuk pedig 15px legyen!

7. Nyissa meg a *nyomtatas.js* állományt, módosítsa a függvényt a következők szerint:

  - A *szelesseg* és a *magassag* konstansok értékeit olvassa ki az űrlap megfelelő mezőiből!
  - A számítás részleteit (*terulet* változó és *papir* konstans értékeit) és a kiszámolt költséget a *valasz* azonosítójú keretben a minta szerinti szövegkörnyezetben jelenítse meg! Az adatokat még a keret láthatóvá tétele előtt írassa a weboldalra!