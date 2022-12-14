Javascript - sovellusharjoitus


1. Avaa koodit VS Code:lla

2. Muokkaa HTML - koodeja. Vaihda sivun nimi sekä sivun alussa olevat ohjeet.

3. Piilota HTML:t, joita ei tarvitse tulostaa.

Lisää ensin CSS - tiedostoon:

@media print {
  .noPrint{
    display:none;
  }
}

Tämän käytä noPrint - luokkaa HTML:ssä, esim. näin,

<button onclick="window.print();" class="noPrint">
Print Me
</button>

Piilota tulostuksesta ohjeet siten, että tulostuksessa näkyy vain iso otsikko.

4. Perusta Github - tili ja lataa koodit sinne

Ohjeita: https://medium.com/@sauravbhagat_10426/how-to-upload-code-to-github-6db1c8ff56aa



