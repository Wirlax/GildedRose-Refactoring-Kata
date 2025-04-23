# Gilded Rose Exercises – GitHub Copilot

Each exercise must be solved only by interacting with GitHub Copilot (no manual code changes).
Use the Gilded Rose codebase in the language of your choice (JavaScript, Python, Java, C#, etc.).

---

## 1. Explainer

**Goal:** Understand how the code works.

**Instruction:**  
Ask Copilot to explain, in your chosen language, how the updateQuality method works, detailing the rules for each item type.

---

## 2. Code & Content Generation

**Goal:** Implement the "Conjured" feature as described in the specification (#file:GildedRoseRequirements_fr.md) in your chosen language.

**Instruction:**  
Ask Copilot to implement the "Conjured" item logic so that "Conjured" items degrade in quality twice as fast as normal items, following all the other business rules.

---

## 3. Testing

**Goal:** Add tests for the new "Conjured" feature.

**Instruction:**  
Ask Copilot to generate unit tests that verify the correct behavior of "Conjured" items, including edge cases (e.g., quality never negative, quality never above 50).

---

## 4. Bug Fixing & Security

**Goal:** Fix a potential bug.

**Pre-step:** Manually introduce a bug in the quality management (for example, allow quality to exceed 50 for a non-Sulfuras item).

**Instruction:**  
Ask Copilot to review the update logic and fix any bug that could allow the quality of an item (except "Sulfuras") to exceed 50 or go below 0.

---

## 5. Refactoring

**Goal:** Improve code readability and maintainability.

**Instruction:**  
Ask Copilot to refactor the updateQuality method to make it more readable and modular, for example by extracting logic per item type into separate functions or classes.

---

## 6. Documentation

**Goal:** Document the main inventory update method (after refactoring).

**Instruction:**  
Ask Copilot to add a clear and complete docstring or JSDoc (depending on the language) to the refactored update method, explaining its purpose, parameters, and business rules.

---

## 7. Code Migration

**Goal:** Migrate the logic to another language and ensure unit tests still work.

**Instruction:**  
Ask Copilot to translate the refactored updateQuality method from one language (e.g., JavaScript) to another (e.g., Python or Java), ensuring all business rules are preserved and that the unit tests still pass.

---
