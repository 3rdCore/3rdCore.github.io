---
name: fix-typos-fr
description: Corrige uniquement les fautes de frappe (orthographe, accents, espaces, majuscules, ponctuation mécanique) d'un texte français dicté, en changeant le moins possible la prononciation, le ton et le flow d'information — les tournures et expressions doivent rester identiques. Use when the user asks to "corriger les typos", fix typos, or clean up dictated French text on this site (e.g. paragraphs in guide-recherche.html).
---

# Corriger les typos (français, minimal)

Ce skill sert à corriger UNIQUEMENT les fautes de frappe d'un texte
français dicté — pas à le réécrire. Le texte cible a généralement été
dicté (reconnaissance vocale), donc les erreurs typiques sont
mécaniques : mots collés, espaces manquants, majuscules au milieu
d'une phrase, accents manquants ou faux, doublons de mots, ponctuation
absente à un endroit évident.

## Ce qu'il faut corriger

- Orthographe et accents (ex: "recemment" → "récemment", "l'apriori" →
  "l'a priori").
- Espaces manquants entre mots collés par la dictée (ex:
  "maintenirun" → "maintenir un").
- Majuscules erronées en milieu de phrase, ou minuscule en début de
  phrase (ex: "les refus que Vous allez" → "les refus que vous
  allez").
- Accords évidents et fautes de grammaire mécaniques directement liées
  à la dictée (ex: pluriel/singulier oublié, "et" pour "est").
- Ponctuation clairement manquante là où la dictée l'a juste omise
  (virgule, point, deux-points) — mais seulement quand c'est sans
  ambiguïté, pas pour "améliorer" le style.
- Mots dupliqués par erreur de dictée.

## Ce qu'il ne faut JAMAIS faire

- Ne change **aucun mot** pour un synonyme, même si un autre mot
  semble "meilleur" stylistiquement. Le choix de vocabulaire de
  l'auteur reste intact.
- Ne reformule et ne restructure **aucune phrase**. La tournure, l'ordre
  des idées et le flow doivent rester identiques à l'original.
- Ne touche pas au registre ni au ton (ex: garde les expressions
  familières comme "des fois" au lieu de "parfois" si c'est ce que
  l'auteur a écrit — ce n'est pas une typo).
- N'ajoute et ne supprime aucune information, exemple, ou nuance.
- Ne "corrige" pas les choix de ponctuation qui sont des préférences de
  style (virgules stylistiques, tirets) — seulement les cas mécaniques
  ci-dessus.
- Si un passage est trop confus pour deviner avec certitude le mot ou
  la tournure voulue par l'auteur (dictée trop garbled), NE DEVINE PAS
  une réécriture : signale le passage à l'utilisateur avec ta meilleure
  hypothèse plutôt que de trancher silencieusement.
- utiliser des &mdash;

## Méthode

1. Identifie le texte ciblé par l'utilisateur (paragraphe, section, ou
   fichier entier s'il ne précise pas).
2. Repère chaque typo mécanique en comparant au texte tel qu'il aurait
   probablement été tapé sans erreur de dictée.
3. Applique les corrections avec l'outil d'édition, phrase par phrase
   si besoin, sans réécrire les parties déjà correctes.
4. Dans ta réponse, résume brièvement les corrections faites (pas
   besoin de recopier tout le paragraphe) et signale explicitement tout
   passage resté ambigu où tu as dû faire une hypothèse.
