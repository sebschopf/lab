# Règles du projet

> Ce fichier est la loi. Tout ce qui est écrit ici s'applique systématiquement.
> Il sera lu systématiquement avant toute modification.

---

##  Règles absolues

| Règle                                                    | Valeur                                         |
|----------------------------------------------------------|------------------------------------------------|
| Pas de Javascript                                        |  Jamais. Jamais. Jamais.... JAMAIS             |
| Seulement OKLCH                                          | Aucune autre modèle de couleur n'est autorisé. |
| Interligne minimum                                       | `1.5`                                          |
| 70 caractères maximum par ligne                          |                                                |
| Jamais de `letter-spacing` négatif                       |                                                |
| Jamais de texte justifié                                 |                                                |
| Toutes les animations sont sous `prefers-reduced-motion` |                                                |
| Aucun border-radius                                      |                                                |
| Aucun blur / glow / ombre floue                          |                                                |

---

##  Organisation des fichiers

| Fichier            | Règles                                                 |
|--------------------|--------------------------------------------------------|
| `style.css`        | STRICT. Toutes les règles s'appliquent.                |
| `pages/*.css`      | LIBRE. On peut tout casser, tout essayer, tout tester. |
| `components/*.css` | EXPERIMENTAL. Peut suivre ou pas les règles.           |

---

## 📝 Conventions

- `kebab-case` uniquement pour les classes
- Séparation stricte forme / couleur
- Un seul composant par classe
- Toutes les couleurs dérivent de `--h-brand`