---
parent: "Català"
nav_order: 5
---

# Resultats

Depenent dels valors mesurats, es determinarà el nivell de tensió arterial.

<img src="../assets/result-yellow.png" width="50%">

En cas de voler obtenir més informació sobre cadascun, cal prémer el símbol que desplegarà la informació. Es pot tancar fent clic fora del quadre o a la X.

<img src="../assets/results-legend.png" width="50%">

## Lògica de resultats

Si el pacient es troba amb una Tensió arterial - Normal, una Hipertensió arterial - Nivell I, o una Hipertensió arterial - Nivell II A, el sistema simplement mostrarà la informació i les recomanacions corresponents a cada valor, sense enviar cap notificació al metge de la patologia.

<img src="../assets/result-yellow.png" width="50%">

Si el pacient es troba amb una Hipertensió arterial - Nivell II B, el sistema enviarà un missatge per Telegram avisant el metge de la patologia, amb les dades obtingudes i les dades del pacient.
<img src="../assets/result-orange.png" width="50%">

En cas que presenti una Hipertensió arterial - Nivell II C, s’enviarà un missatge per Telegram i també es desplegarà una opció per comunicar-se per telèfon amb el metge.

<img src="../assets/result-red.png" width="50%">
