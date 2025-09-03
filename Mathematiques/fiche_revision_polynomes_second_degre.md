# Fiche de Révision : Les Polynômes du Second Degré

Cette fiche vous guide à travers tout ce que vous devez savoir sur les polynômes du second degré pour la classe de première.

---

## 1. Qu'est-ce qu'un polynôme du second degré ?

C'est une fonction `f` définie sur ℝ par :
`f(x) = ax² + bx + c`

Où `a`, `b`, et `c` sont des réels et, très important, **`a` doit être différent de 0**.

- **`ax² + bx + c`** est la **forme développée**.
- La représentation graphique est toujours une **parabole**.

---

## 2. Le Discriminant `Δ` : La Clé de Tout !

Pour analyser un polynôme, on calcule TOUJOURS en premier le discriminant, noté `Δ` (delta).

**Formule : `Δ = b² - 4ac`**

La valeur de `Δ` va tout nous dire sur le polynôme.

---

## 3. Les Racines (Solutions de l'équation `ax² + bx + c = 0`)

Les "racines" sont les valeurs de `x` pour lesquelles le polynôme est égal à zéro. Graphiquement, ce sont les points où la parabole coupe l'axe des abscisses.

Tout dépend du signe de `Δ` :

#### Cas 1 : `Δ > 0` (Positif)
Le polynôme a **deux racines réelles distinctes** :
- `x₁ = (-b - √Δ) / 2a`
- `x₂ = (-b + √Δ) / 2a`

#### Cas 2 : `Δ = 0` (Nul)
Le polynôme a **une seule racine réelle "double"** :
- `x₀ = -b / 2a`

#### Cas 3 : `Δ < 0` (Négatif)
Le polynôme n'a **aucune racine réelle**. L'équation `ax² + bx + c = 0` n'a pas de solution dans ℝ.

---

## 4. Factorisation du Polynôme

La factorisation dépend aussi directement du discriminant :

- Si `Δ > 0` : `f(x) = a(x - x₁)(x - x₂)`
- Si `Δ = 0` : `f(x) = a(x - x₀)²`
- Si `Δ < 0` : On **ne peut pas factoriser** le polynôme dans les réels.

---

## 5. Signe du Polynôme

Pour savoir quand `f(x)` est positif ou négatif, on retient une règle simple :

> Le polynôme est **"du signe de `a` à l'extérieur des racines"**.

- **Si `Δ > 0`** : Le polynôme est du signe de `a` avant `x₁` et après `x₂`, et du signe opposé (`-a`) entre les racines.
- **Si `Δ = 0` ou `Δ < 0`** : Le polynôme est toujours du signe de `a` (sauf en `x₀` où il vaut 0 si `Δ = 0`).

---

## 6. Représentation Graphique (La Parabole)

- **Si `a > 0`** : La parabole est "souriante" (tournée vers le haut). Elle admet un minimum.
- **Si `a < 0`** : La parabole "fait la tête" (tournée vers le bas). Elle admet un maximum.

Le sommet `S` de la parabole a pour abscisse `α = -b / 2a`. (C'est la même formule que la racine double !).

---

## Tableau Récapitulatif

| Discriminant `Δ` | Racines (Solutions de `f(x)=0`) | Factorisation | Signe de `f(x)` |
| :--- | :--- | :--- | :--- |
| **`Δ > 0`** | 2 racines distinctes `x₁` et `x₂` | `a(x - x₁)(x - x₂)` | Signe de `a` à l'extérieur des racines |
| **`Δ = 0`** | 1 racine double `x₀` | `a(x - x₀)²` | Toujours du signe de `a` (nul en `x₀`) |
| **`Δ < 0`** | Aucune racine réelle | Pas de factorisation | Toujours du signe de `a` |

---

## Exemple Concret

Soit le polynôme `f(x) = 2x² - 4x - 6`.

1.  **Identification** : `a = 2`, `b = -4`, `c = -6`.
2.  **Calcul de `Δ`** :
    `Δ = (-4)² - 4 * 2 * (-6) = 16 + 48 = 64`
3.  **Analyse de `Δ`** :
    `Δ = 64 > 0`, donc il y a deux racines distinctes. `√Δ = √64 = 8`.
4.  **Calcul des racines** :
    - `x₁ = (-(-4) - 8) / (2 * 2) = (4 - 8) / 4 = -4 / 4 = -1`
    - `x₂ = (-(-4) + 8) / (2 * 2) = (4 + 8) / 4 = 12 / 4 = 3`
    Les racines sont **-1** et **3**.
5.  **Factorisation** :
    `f(x) = 2(x - (-1))(x - 3) = 2(x + 1)(x - 3)`
6.  **Signe** :
    `a = 2` est positif. Donc `f(x)` est positif à l'extérieur des racines `]-∞, -1[` et `]3, +∞[`, et négatif entre les racines `]-1, 3[`.
