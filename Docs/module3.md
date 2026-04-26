# Module 3 – Calculs de base

## Objectif pédagogique
À l’issue de ce module, l’apprenant sera capable de :
- Comprendre le fonctionnement des formules dans Excel
- Utiliser les opérations mathématiques de base
- Comprendre la syntaxe d’une fonction (structure et arguments)
- Utiliser les fonctions les plus courantes
- Recopier des formules efficacement

---

## 1. Introduction aux calculs dans Excel

Dans Excel, tous les calculs commencent par une formule.

Une formule est une expression qui commence toujours par le signe égal (=).  
Elle permet d’effectuer un calcul en utilisant des nombres ou des cellules.

Exemple :
= A1 + B1

Cela signifie : additionner la valeur de A1 et de B1.

---

## 2. Les opérations de base

Excel utilise des symboles simples pour les calculs :

| Opération        | Symbole | Exemple        |
|-----------------|--------|----------------|
| Addition        | +      | =A1 + B1       |
| Soustraction    | -      | =A1 - B1       |
| Multiplication  | *      | =A1 * B1       |
| Division        | /      | =A1 / B1       |

Conseil :  
Toujours utiliser les cellules plutôt que les valeurs directement pour garder des calculs dynamiques.

---

## 3. Comprendre les références de cellules

Une référence de cellule permet d’utiliser une valeur sans la recopier.

Exemple :
Si A1 = 5000 et B1 = 3000  
Alors :

= A1 + B1 → donne 8000

Si vous modifiez A1, le résultat change automatiquement.

---

## 4. Les fonctions dans Excel

### 4.1 Définition
Une fonction est une formule déjà prête qui effectue un calcul spécifique.

---

### 4.2 Syntaxe d’une fonction

Structure générale :

= NOM_FONCTION(argument1 ; argument2 ; ...)

Explication simple :
- Le signe = indique un calcul
- Le nom de la fonction indique ce que vous voulez faire
- Les arguments sont les données utilisées dans le calcul

---

## 5. Les fonctions les plus utilisées (niveau débutant)

Nous allons voir les fonctions essentielles que vous utiliserez très souvent.

---

### 5.1 Fonction SOMME

Objectif : additionner plusieurs valeurs

Syntaxe :
= SOMME(plage)

Exemple :
= SOMME(B2:B5)

Cela additionne toutes les valeurs de B2 à B5.

---

### 5.2 Fonction MOYENNE

Objectif : calculer la moyenne

Syntaxe :
= MOYENNE(plage)

Exemple :
= MOYENNE(B2:B5)

Cela calcule la moyenne des valeurs.

---

### 5.3 Fonction MIN

Objectif : trouver la plus petite valeur

Syntaxe :
= MIN(plage)

Exemple :
= MIN(B2:B5)

---

### 5.4 Fonction MAX

Objectif : trouver la plus grande valeur

Syntaxe :
= MAX(plage)

Exemple :
= MAX(B2:B5)

---

### 5.5 Fonction NB

Objectif : compter le nombre de cellules contenant des nombres

Syntaxe :
= NB(plage)

Exemple :
= NB(B2:B5)

---

### 5.6 Fonction NBVAL

Objectif : compter les cellules non vides

Syntaxe :
= NBVAL(plage)

Exemple :
= NBVAL(A2:A5)

---

### 5.7 Fonction SI

Objectif : faire un test logique

Syntaxe :
= SI(condition ; valeur_si_vrai ; valeur_si_faux)

Explication simple :
- condition : ce que vous testez
- valeur_si_vrai : résultat si la condition est vraie
- valeur_si_faux : résultat si la condition est fausse

Exemple :
= SI(B2 > 30000 ; "Élevé" ; "Faible")

---

## 6. Recopie des formules

### 6.1 Principe
Vous n’avez pas besoin de retaper une formule plusieurs fois.

---

### 6.2 Méthode
- Cliquer sur la cellule contenant la formule
- Faire glisser le petit carré en bas à droite (poignée de recopie)

---

### 6.3 Résultat
Excel adapte automatiquement les références.

---

## 7. Cas pratique

### 7.1 Objectif
Calculer et analyser des dépenses mensuelles.

---

### 7.2 Étapes

1. Saisir les données :

| A            | B      |
|--------------|--------|
| Loyer        | 150000 |
| Nourriture   | 50000  |
| Transport    | 20000  |
| Internet     | 15000  |

2. Calculer le total :
= SOMME(B2:B5)

3. Calculer la moyenne :
= MOYENNE(B2:B5)

4. Trouver la dépense minimale :
= MIN(B2:B5)

5. Trouver la dépense maximale :
= MAX(B2:B5)

6. Ajouter une colonne C pour analyse :

Dans C2 :
= SI(B2 > 30000 ; "Dépense élevée" ; "Dépense normale")

Recopier vers le bas

---

### 7.3 Résultat attendu
Un tableau avec :
- total
- moyenne
- minimum
- maximum
- classification des dépenses

---

## 8. Bonnes pratiques

- Toujours commencer par =
- Vérifier les parenthèses
- Utiliser des plages (ex : B2:B5)
- Ne pas mélanger texte et nombres
- Tester les formules avec de petites données

---

## 9. Évaluation des acquis

Répondre à la question suivante :

Explique avec tes mots la structure d’une fonction Excel et donne un exemple simple.

---
