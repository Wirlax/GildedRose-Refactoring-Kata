# Exercices Gilded Rose – GitHub Copilot

Chaque exercice doit être résolu uniquement en dialoguant avec GitHub Copilot (pas de modification manuelle du code).  
Utilisez la base de code Gilded Rose dans le langage de votre choix (JavaScript, Python, Java, C#, etc.).

---

## 1. Explainer

**Objectif** : Comprendre le fonctionnement du code.

**Consigne** :  
Ask Copilot to explain, in your chosen language, how the updateQuality method works, detailing the rules for each item type.

---

## 2. Code & Content Generation

**Objectif** : Implémenter la fonctionnalité "Conjured" décrite dans la spécification (#file:GildedRoseRequirements_fr.md) dans le langage de votre choix.

**Consigne** :  
Ask Copilot to implement the "Conjured" item logic so that "Conjured" items degrade in quality twice as fast as normal items, following all the other business rules.

---

## 3. Testing

**Objectif** : Ajouter des tests pour la nouvelle fonctionnalité "Conjured".

**Consigne** :  
Ask Copilot to generate unit tests that verify the correct behavior of "Conjured" items, including edge cases (e.g., quality never negative, quality never above 50).

---

## 4. Bug Fixing & Security

**Objectif** : Corriger un bug potentiel.

**Étape préalable** : Introduisez manuellement un bug dans la gestion de la qualité (par exemple, permettez à la qualité de dépasser 50 pour un item non Sulfuras).

**Consigne** :  
Ask Copilot to review the update logic and fix any bug that could allow the quality of an item (except "Sulfuras") to exceed 50 or go below 0.

---

## 5. Refactoring

**Objectif** : Améliorer la lisibilité et la maintenabilité du code.

**Consigne** :  
Ask Copilot to refactor the updateQuality method to make it more readable and modular, for example by extracting logic per item type into separate functions or classes.

---

## 6. Documentation

**Objectif** : Documenter la méthode principale de mise à jour de l’inventaire (après refactoring).

**Consigne** :  
Ask Copilot to add a clear and complete docstring or JSDoc (selon le langage) to the refactored update method, explaining its purpose, parameters, and business rules.

---

## 7. Code Migration

**Objectif** : Migrer la logique vers un autre langage et s'assurer que les tests unitaires fonctionnent toujours.

**Consigne** :  
Ask Copilot to translate the refactored updateQuality method from one language (e.g., JavaScript) to another (e.g., Python or Java), ensuring all business rules are preserved and that the unit tests still pass.

---