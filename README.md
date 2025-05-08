<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>Fatti Casuali</title>
</head>
<body>

  <h1>Fatto Casuale</h1>
  <button onclick="mostraFatto()">Mostra Fatto</button>
  <p id="fatto">Clicca per scoprire un fatto!</p>

  <script>
    const fatti = [
      "Le zebre sono nere con strisce bianche.",

"Gli squali non hanno ossa, ma cartilagine.",

"Il cervello umano è composto per il 75% di acqua.",

"I canguri non possono camminare all'indietro.",

"Un giorno su Venere è più lungo di un anno su Venere.",

"L'olio di oliva è stato utilizzato per scopi medicinali fin dall'antichità.",

"La Terra non è una sfera perfetta, ma una forma oblunga.",

"Gli scimpanzé condividono il 98% del loro DNA con gli esseri umani.",

"I pinguini sono monogami e formano coppie per tutta la vita.",

"I coccodrilli non possono sporgere la lingua.",

"Il miele è l'unico alimento che non va mai a male, anche dopo migliaia di anni.",
    ];

    function mostraFatto() {
      const indice = Math.floor(Math.random() * fatti.length);
      document.getElementById("fatto").innerText = fatti[indice];
    }
  </script>

</body>
</html>
