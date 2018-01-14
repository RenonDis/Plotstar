# Interactive Data Visualization (ECL MOS 5.5)

Professeur : [Romain Vuillemot](http://www.ec-lyon.fr/contacts/romain-vuillemot), *LIRS/MI École Centrale de Lyon*

## Question 1 : Dataset Iris

<table border="0">
  <tr>
    <td>
      <img src="img/irisViz.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td>
      Visualisation des données Iris avec espèces par couleur, et effectif par taille
    </td>
  </tr>
</table>

## Question 2 : Dataset Movies

Le dataset *us-election* fourni n'a pas pu être correctement lu par *PoleStar*. Un dataset alternatif a été choisi.
Nous avons donc choisi le dataset *Movies* en cherchant à montrer un lien entre sa popularité, caractérisée par sa note *IMDB*, croisée avec l'équivalent *Rotten Tomatoes*, et le budget alloué, ainsi que les revenus dégagés.

<table border="0">
  <tr>
    <td>
      <img src="img/imdbProd.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td>
      Visualisation des données Movie : argent et popularité
    </td>
  </tr>
</table>

Le dégradé *Rotten Tomatoes* vérifie plutôt bien les notes *IMDB*. Il ressort de cette visualisation qu'à partir d'une note de 6, le budget alloué semble avoir moins d'impact sur la popularité et les chiffres d'affaire réalisés.

## Question 3 : Dataset Stocks

### Visualisation des données Stocks en ligne par cours selon le symbole, couleur par symbole

<table border="0">
  <tr>
    <td>
      <img src="img/multLineStocks.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td>
      Visualisation des données Stocks par cours selon le symbole, couleur par symbole
    </td>
  </tr>
</table>

### Visualisation des données Stocks en barres par cours groupée par symbole

Pour cette visualisation, la largeur des barres est aussi fonctions du symbole, pour que les barres d'un symbole ne cachent pas celle d'un autre en se superposant.

<table border="0">
  <tr>
    <td>
      <img src="img/SizeColorStocks.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td>
      Visualisation des données Stocks par cours selon le symbole groupée par symbole
    </td>
  </tr>
</table>

### Visualisation de l'amplitude des données Stocks et de leur densité

Pour cette visualisation, nous avons choisi d'afficher pour chaque symbole la répartition de ses prix sur son amplitude, pour voir les zones dans lesquelles les prix se retrouvent le plus fréquemment.

<table border="0">
  <tr>
    <td>
      <img src="img/AmplStocks.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td>
      Visualisation de l'amplitude des données Stocks et de leur densité
    </td>
  </tr>
</table>
