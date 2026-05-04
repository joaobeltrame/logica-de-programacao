# logica-de-programacao
Exercícios de lógica de programação e tabelas verdade
# Lógica de Programação - Prática de Conectivos 🚀

Este repositório contém a resolução dos exercícios de lógica proposicional da formação da Rocketseat. O objetivo é fortalecer o raciocínio lógico aplicado à programação.

## 📝 Exercícios de Tabela Verdade

### 1. Conjunção (E - ∧)
**Frase:** "Eu estudei para a prova e fiz todos os exercícios."
- **Expressão:** `p ∧ q`

| p | q | p ∧ q |
| :--- | :--- | :--- |
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **F** |

---

### 2. Disjunção (OU - ∨)
**Frase:** "Eu vou ao cinema ou fico em casa assistindo séries."
- **Expressão:** `p ∨ q`

| p | q | p ∨ q |
| :--- | :--- | :--- |
| V | V | **V** |
| V | F | **V** |
| F | V | **V** |
| F | F | **F** |

---

### 3. Condicional (SE... ENTÃO - →)
**Frase:** "Se eu acordar cedo, então conseguirei pegar o ônibus."
- **Expressão:** `p → q`

| p | q | p → q |
| :--- | :--- | :--- |
| V | V | **V** |
| V | F | **F** |
| F | V | **V** |
| F | F | **V** |

---

### 4. Bicondicional (SE E SOMENTE SE - ↔)
**Frase:** "Eu farei um bolo se e somente se comprar os ingredientes."
- **Expressão:** `p ↔ q`

| p | q | p ↔ q |
| :--- | :--- | :--- |
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **V** |

---

### 5. Expressão Composta (Condicional + Conjunção)
**Frase:** "Se eu estudar muito, então passarei na prova e ganharei um presente."
- **Expressão:** `p → (q ∧ r)`

| p | q | r | q ∧ r | p → (q ∧ r) |
| :--- | :--- | :--- | :--- | :--- |
| V | V | V | V | **V** |
| V | V | F | F | **F** |
| V | F | V | F | **F** |
| V | F | F | F | **F** |
| F | V | V | V | **V** |
| F | V | F | F | **V** |
| F | F | V | F | **V** |
| F | F | F | F | **V** |

---

## 🛠️ Conexão com a Programação
Os conectivos lógicos são a base para as estruturas condicionais:
- `&&` (AND / E)
- `||` (OR / OU)
- `!` (NOT / NEGAÇÃO)

---
Feitopor João Beltrame
