---
clavier: true
gestionGrosMots: true
rechercheContenu: false
---

# Titre du chatbot

Message initial qui apparaît au lancement du chatbot.

- il peut y avoir une liste dans le message
- ou tout autre **formatage** en _Markdown_

À la fin du message, on peut guider l'utilisateur avec des choix possibles

1. [J'aimerais savoir comment rédiger une réponse du chatbot](Rédaction réponse)
2. [Qu'est-ce qui déclenche l'apparition de cette réponse ?](Déclenchement)

## Rédaction réponse

Chaque titre de niveau 2 définit une réponse possible du chatbot.
On écrit cette **réponse** en _Markdown_.

On peut utiliser les emojis :+1:, insérer des [liens](https://eyssette.forge.aeif.fr/chatMD/), ou des images (et même préciser la dimension) :

![descriptif de l'image](https://picsum.photos/100)

![descriptif de l'image](https://picsum.photos/100 =300x150) 
<!--commentaire invisible : j'ai précisé ci-dessus la dimension de l'image avec l'indication =300x150 -->

- on peut faire des listes
- mais il ne faut pas que la liste commence immédiatement après le titre 2
- car sinon elle sera considérée comme une liste de mots déclencheurs pour la réponse

## Déclenchement
- déclenchement
- déclenche

Une réponse du chatbot apparaît :
- Si un lien vers cette réponse a été définie dans une option à la fin d'une réponse, pour guider l'utilisateur
- Ou bien si l'utilisateur écrit une réponse qui contient les mots ou expression clés. Le chatbot fait d'abord une recherche d'identité stricte, puis de simples similarités afin de choisir la réponse la plus pertinente

1. [Comment on guide l'utilisateur avec des options à la fin d'une réponse ?](Guider l'utilisateur)

## Guider l'utilisateur
- options
- guider

On peut guider l'utilisateur en laissant à la fin de la réponse (et seulement à la fin) des options.
On fait une liste ordonnée (un chifre puis un point) et on écrit un lien dans chaque item avec l'intitulé de l'option et le titre de l'option, qui doit correspondre à un des titres de niveau 2.
Si on veut permettre le retour au message initial, on laisse le lien vide.

1. [Intitulé option 1](option 1)
2. [Intitulé option 2](option 2)
3. [Retour au message initial]()

## option 1
Voici la première option.

## option 2
Voici la deuxième option



