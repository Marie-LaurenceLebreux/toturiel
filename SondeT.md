# Sonde de temperature

## Étape 1 

Dans la section extension, rechercher l'extension Dstemp

## Étape 2

Sélectionner l'extension suivante

## Étape 3 

Sélectionner le bloc TOUJOURS et inserer la fonction SERIE 

```blocks
basic.forever(function () {
    serial.writeValue("x", 0)
})
````