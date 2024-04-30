---
parent: "Castellano"
nav_order: 5
---

# Resultados

Dependiendo los valores medidos, se determinará el nivel de tensión arterial. 

<img src="../assets/result-yellow.png" width="50%">

En caso de querer obtener más información sobre cada uno, ha de presionar el símbolo que desplegará información. Puede cerrarlo haciendo clic por fuera del mismo o en la X. 

<img src="../assets/results-legend.png" width="50%">

## Logica de resultados

Si el paciente se encuentra con una *Tensión arterial - Normal*, con una *Hipertensión arterial - Nivel I*, o con una *Hipertensión arterial - Nivel II A*, el sistema simplemente mostrará la información y las recomendaciones correspondiente a cada valor sin enviar ninguna notificación al médico de la patología.

<img src="../assets/result-yellow.png" width="50%">

Si el paciente se encuentra con una Hipertensión arterial - Nivel II B, el sistema enviará un mensaje por Telegram dando aviso al médico de la patología, los datos obtenidos y los datos del paciente. 

<img src="../assets/result-orange.png" width="50%">

En caso de que tenga una Hipertensión arterial - Nivel II C, se enviará un mensaje por Telegram y también se desplegará una opción para comunicarse por teléfono con el médico.  

<img src="../assets/result-red.png" width="50%">