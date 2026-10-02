<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mes listes</title>
</head>
<body>

    <h1>Mes listes</h1>

    <h2>Liste non ordonnée</h2>
    <ul>
        <li>Pomme</li>
        <li>Banane</li>
        <li>Orange</li>
    </ul>

    <h2>Liste ordonnée</h2>
    <ol>
        <li>Ouvrir le navigateur</li>
        <li>Créer une nouvelle page</li>
        <li>Enregistrer le fichier</li>
    </ol>

    <h2>Liste imbriquée</h2>
    <ul>
        <li>Fruits
            <ul>
                <li>Pomme</li>
                <li>Banane</li>
            </ul>
        </li>
        <li>Légumes
            <ul>
                <li>Carotte</li>
                <li>Tomate</li>
            </ul>
        </li>
    </ul>

</body>
</html>




Les listes en HTML
En HTML, on utilise des listes pour afficher plusieurs éléments les uns à la suite des autres.

Il existe principalement deux types de listes :

<ul> : une liste à puces

<ol> : une liste numérotée

<li> : un élément de la liste

1. La liste à puces avec <ul>
<ul> signifie Unordered List, c'est-à-dire « liste non ordonnée ».

Chaque élément est placé dans une balise <li>.

<ul>
  <li>Pomme</li>
  <li>Banane</li>
  <li>Orange</li>
</ul>

Cela donnera :

Pomme

Banane

Orange

2. La liste numérotée avec <ol>
<ol> signifie Ordered List, c'est-à-dire « liste ordonnée ».

Le navigateur ajoute automatiquement les numéros.

<ol>
  <li>Se lever</li>
  <li>Prendre son petit-déjeuner</li>
  <li>Aller à l'école</li>
</ol>

Cela donnera :

Se lever

Prendre son petit-déjeuner

Aller à l'école

3. À quoi sert <li> ?
<li> signifie List Item, c'est-à-dire « élément de liste ».

Il faut mettre chaque élément dans une balise <li>.

Par exemple :

<ul>
  <li>Rouge</li>
  <li>Vert</li>
  <li>Bleu</li>
</ul>

Ici, il y a 3 éléments dans la liste.
