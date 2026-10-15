# AGENTS.md — Règles permanentes de travail

## Style de code
- Noms de variables en anglais, snake_case.
- Noms de classes en PascalCase, sans abréviation.
- Noms de dossiers en minuscules, sans tirets, sans underscores.
- Pas de noms génériques : data, temp, foo, test1, tmp.
- Commentaires concis, en anglais, uniquement si nécessaire.
- Code de niveau production, lisible par un ingénieur senior.

## Architecture
- Séparation claire : ingestion, transformation, stockage, exposition.
- Un module = une responsabilité.
- Pas de dépendances inutiles.

## Interdits
- Ne jamais hardcoder de chemins absolus.
- Ne jamais commit sans test.
- Ne jamais utiliser "tmp", "test", "foo", "bar" comme noms.

## Processus
- Avant de coder : lire `memory/PROJECT.md` et `memory/STATE.md`.
- Après avoir codé : mettre à jour `memory/STATE.md` et `memory/LOG.md`.
- Un commit = un changement logique, testable, documenté.

## Règle absolue — Communication
- **Ne jamais écrire `/oc` ou `/opencode` dans tes réponses.**
- Ces mots-clés déclenchent un nouveau workflow, ce qui crée une boucle infinie.
- Si tu dois mentionner une commande, écris-la comme ceci : `slash-oc` ou `commande oc`.
- Tes réponses doivent être descriptives, pas des commandes.
## Règle absolue — Communication
- **Ne jamais écrire `/oc` ou `/opencode` dans tes réponses.**
- Si tu dois mentionner une commande, écris `slash-oc` ou `commande oc`.
