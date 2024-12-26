# Daily Coding Challenge - 2024

Questo repository raccoglie una serie di micro progetti giornalieri per il 2024, ognuno focalizzato su concetti di programmazione e sfide. Ogni progetto sarà contrassegnato con argomenti rilevanti, creando un portfolio diversificato nel corso dell'anno.

## Quadratini Personalizzabili

In questa sezione, troverai 360 quadratini numerati. Ogni quadrato rappresenta un giorno dell'anno. Puoi inserire un numero e vedere il colore del quadrato cambiare in base al numero: se il numero è maggiore di 180, il quadrato avrà uno sfondo verde; altrimenti, avrà uno sfondo rosso. I quadrati con numeri da 1 a 180 avranno uno sfondo neutro.

### Visualizzazione dei Quadrati

```html
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quadratini Challenge</title>
    <style>
        .grid-container {
            display: grid;
            grid-template-columns: repeat(30, 1fr);
            gap: 5px;
            margin: 20px;
        }
        .square {
            width: 30px;
            height: 30px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 14px;
            border-radius: 5px;
        }
        .green-bg {
            background-color: green;
            color: white;
        }
        .red-bg {
            background-color: red;
            color: white;
        }
        .neutral-bg {
            background-color: #ccc;
            color: black;
        }
    </style>
</head>
<body>

    <div class="grid-container">
        <!-- Esempio di quadratini numerati -->
        <div class="square green-bg">1</div>
        <div class="square red-bg">2</div>
        <div class="square neutral-bg">3</div>
        <!-- Aggiungi qui gli altri quadratini -->
    </div>

</body>
</html>
