# Daily Coding Challenge - 2024

Questo repository raccoglie una serie di micro progetti giornalieri per il 2024, ognuno focalizzato su concetti di programmazione e sfide. Ogni progetto sarà contrassegnato con argomenti rilevanti, creando un portfolio diversificato nel corso dell'anno.

## Quadrati Personalizzabili

In questa sezione, troverai 365 quadratini numerati, uno per ogni giorno dell'anno. Ogni quadrato rappresenta un giorno dell'anno e il colore del quadrato cambia in base al numero. Se il numero è maggiore di 180, il quadrato avrà uno sfondo verde, se il numero è inferiore o uguale a 180, avrà uno sfondo rosso. I quadrati da 1 a 180 avranno uno sfondo neutro (grigio).

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
            font-size: 12px;
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
        <!-- Esempio di quadratini numerati con colorazioni -->
        <div class="square green-bg">1</div>
        <div class="square green-bg">2</div>
        <div class="square green-bg">3</div>
        <div class="square green-bg">4</div>
        <div class="square green-bg">5</div>
        <div class="square green-bg">6</div>
        <div class="square green-bg">7</div>
        <div class="square green-bg">8</div>
        <div class="square green-bg">9</div>
        <div class="square green-bg">10</div>
        <div class="square green-bg">11</div>
        <div class="square green-bg">12</div>
        <div class="square green-bg">13</div>
        <div class="square green-bg">14</div>
        <div class="square green-bg">15</div>
        <div class="square green-bg">16</div>
        <div class="square green-bg">17</div>
        <div class="square green-bg">18</div>
        <div class="square green-bg">19</div>
        <div class="square green-bg">20</div>
        <div class="square green-bg">21</div>
        <div class="square green-bg">22</div>
        <div class="square green-bg">23</div>
        <div class="square green-bg">24</div>
        <div class="square green-bg">25</div>
        <div class="square green-bg">26</div>
        <div class="square green-bg">27</div>
        <div class="square green-bg">28</div>
        <div class="square green-bg">29</div>
        <div class="square green-bg">30</div>
        <!-- Aggiungere altri quadratini fino a 365 -->
    </div>

</body>
</html>
