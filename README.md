# Bingo
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Wedding Reception Bingo</title>
<style>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    max-width: 800px;
    margin: auto;
}
.grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 5px;
}
.square {
    border: 1px solid #ccc;
    padding: 20px 10px;
    cursor: pointer;
    min-height: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.marked {
    background-color: #8ecae6;
    color: white;
}
</style>
</head>
<body>

<h1>Wedding Reception Bingo</h1>

<div class="grid">
    <div class="square">Celebrate</div>
    <div class="square">Dancing Queen</div>
    <div class="square">Hot In Herre</div>
    <div class="square">Low</div>
    <div class="square">Mr. Brightside</div>

    <div class="square">Yeah!</div>
    <div class="square">Shut Up and Dance</div>
    <div class="square">Don't Stop Believin'</div>
    <div class="square">I Wanna Dance With Somebody</div>
    <div class="square">September</div>

    <div class="square">Cupid Shuffle</div>
    <div class="square">I Gotta Feeling</div>
    <div class="square">FREE SPACE</div>
    <div class="square">Come On Eileen</div>
    <div class="square">All The Small Things</div>

    <div class="square">Sweet Caroline</div>
    <div class="square">Gasolina</div>
    <div class="square">Love Story</div>
    <div class="square">24K Magic</div>
    <div class="square">Crazy In Love</div>

    <div class="square">The Middle</div>
    <div class="square">Levitating</div>
    <div class="square">Party In The USA</div>
    <div class="square">Man! I Feel Like a Woman!</div>
    <div class="square">Bingo!</div>
</div>

<script>
document.querySelectorAll('.square').forEach(square => {
  square.addEventListener('click', () => {
    square.classList.toggle('marked');
