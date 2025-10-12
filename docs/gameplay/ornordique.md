---
sidebar_position: 15
---

# 🥇 Or nordique

L’**or nordique** est une **seconde monnaie** en jeu, **non utilisable** pour les transactions entre joueurs.

Cette monnaie fonctionne comme une **bourse** : le prix est **entièrement régulé par les joueurs** (achats/reventes).  
La valeur peut aller de **quelques centimes** à **plusieurs millions** — **sans limite**.

> Lors d’un achat, une **taxe croissante (exponentielle)** s’applique : plus vous achetez en une fois, plus la taxe augmente.

---

## 📈 Principe

- Le prix **varie uniquement** lorsque des joueurs **achètent** ou **revendent**.  
  S’il n’y a **aucune transaction**, le prix **ne bouge pas**.
- Vous pouvez obtenir une **quantité illimitée** d’or nordique, mais le **coût total augmente fortement** avec la quantité (taxe + hausse progressive du prix).
- Lors d’un **gros achat**, le prix **monte à chaque unité** achetée (comme si vous achetiez **une par une**).  
  → Le coût **n’est pas** simplement `quantité × prix de départ`.

---

## 🧪 Mise en situation (exemple indicatif)

> *Les chiffres ci-dessous sont illustratifs ; les montants réels dépendent du marché.*

- Un joueur A achète **200** or à **10 $/u**. Il paie **~2 500 $** au total (taxe et hausse incluses). Le prix monte à **15 $**.  
- Un joueur B achète **50** or à **15 $/u**. Il paie **~900 $**. Le prix monte à **22 $**.  
- Comme le prix a monté, le joueur A peut **revendre** ses **200** ors et **gagner plus** que son investissement initial.

---

## ⌨️ Commandes

| Commande | Description |
|----------|-------------|
| **/or buy \<quantité\>** | Acheter de l’or nordique. |
| **/or sell \<quantité\>** | Revendre de l’or nordique. |
| **/or check \<quantité\>** | Estimer le **coût total** d’un achat (taxe + progression de prix). |
