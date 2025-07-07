---
sidebar_position: 4
---

# 💫 Équipage

**Un équipage** est une communauté regroupée autour d’une survie et régie par une organisation hiérarchique, tel qu'un chef, des officiers, les membres d'équipage ainsi que les recrues.

---

## 🎨 Code couleurs et style

En ce qui concerne les couleurs, aucune restriction ne vous est imposée. Vous pouvez donc mettre plusieurs couleurs, comme bon vous semble.

:::tip Important
Toutefois, le code _Magic_ est **interdit**. Dans le cas où vous l'utiliseriez, il vous sera demandé de modifier votre préfixe d'équipage.  
En cas de refus, une sanction et une suppression de l'équipage peuvent être engendrées.
:::

---

## 🛠️ Créer un équipage

Utilisez la commande suivante pour créer Un équipage :

```bash
/equipage create <nom>
```

Ensuite, pour valider ou annuler, faites :

```bash
/equipage confirm
```

ou

```bash
/equipage cancel
```

---

## ❓ Difficulté à créer votre équipage ?

:::info ℹ️
Si un message d'erreur s'affiche lorsque vous essayez de créer un équipage :
:::

- **Vérifiez que vous n'utilisez pas de caractères spéciaux** : Les caractères spéciaux ne sont pas acceptés et peuvent bloquer la création.
- **Vérifiez que le nom choisi n'est pas trop long** : Si c'est le cas, suivez ces étapes :

1. Créez votre équipage avec un nom plus court, par exemple :
   ```bash
   /e create Redstone
   ```
2. Validez avec :
   ```bash
   /e confirm
   ```
3. Modifiez le préfixe avec :
   ```bash
   /e prefix RedstoneTorchElec
   ```

---

## ❌ Supprimer Un équipage

Pour supprimer votre équipage, utilisez cette commande :

```bash
/e delete
```

Confirmez ou annulez avec :

```bash
/e confirm
```

ou

```bash
/e cancel
```

---

## 🤝 Inviter quelqu'un dans Un équipage

Pour inviter quelqu'un, utilisez la commande suivante :

```bash
/e invite <pseudo>
```

Le joueur invité doit accepter avec :

```bash
/e join <équipage>
```

ou

```bash
/e accept <équipage>
```

---

## ⚔️ Quels sont les avantages ?

:::tip 🏆
Créer Un équipage vous permet de montrer votre coopération avec vos amis, de former un groupe de joueurs économiquement ou en combat.
:::

Vous pouvez également activer un chat privé entre les membres avec :

```bash
/e chat
```

Désactivez-le avec la même commande.

---

## 📈 Promouvoir et rétrograder

En tant que chef, vous pouvez gérer la hiérarchie de votre équipage.

**Rangs disponibles :**
- Chef 👑
- Officier 🛡️
- Membre 👥
- Recrue 🎓

Pour promouvoir un joueur, utilisez :

```bash
/e promote <pseudo>
```

Pour rétrograder un joueur, utilisez :

```bash
/e demote <pseudo>
```

Pour expulser un joueur, utilisez :

```bash
/e kick <pseudo>
```

---

## 🏠 Gérer le spawn de l'équipage

Pour définir un home d'équipage, placez-vous à l'endroit souhaité et utilisez :

```bash
/e sethome
```

Supprimez-le avec :

```bash
/e delhome
```

Téléportez-vous au home d'équipage avec :

```bash
/e home
```

---

## 📋 Les informations de l'équipage

Utilisez la commande suivante pour afficher les infos de votre équipage :

```bash
/e info
```

Vous verrez :
- **Le lingot d'or 🪙** : indique la somme dans la banque.
- **Le casque en fer ⛑️** : affiche les membres et leurs connexions.
- **L'émeraude 💎** : montre le statut (public/privé).
- **Le lit 🛏️** : home d'équipage.
- **Le coffre 🧰** : stockage commun.

---

## 🚀 Upgrade un équipage

Vous pouvez augmenter le niveau de votre équipage pour plus d'avantages :

- **Augmentation du nombre de membres**.
- **Accès à plus de coffres d'équipage**.

Pour upgrader, déposez la somme nécessaire avec :

```bash
/e bank deposit <somme>
```

Puis faites :

```bash
/e upgrade
/e confirm
```

### 📈 Passage au niveau 2
- Somme : 25.000 $
- 5 membres max.

### 📈 Passage au niveau 3
- Somme : 50.000 $
- 10 membres max.

### 📈 Passage au niveau 4
- Somme : 75.000 $
- 15 membres max.

### 📈 Passage au niveau 5
- Somme : 100.000 $
- 25 membres max.

---

## 🔧 Commandes

Voici quelques commandes pratiques :

- `/e bank balance` → Affiche l'argent de l'équipage.
- `/e bank deposit <montant>` → Dépose de l'argent dans la banque.
- `/e bank withdraw <montant>` → Retire de l'argent.
- `/e vault` → Ouvre le coffre commun.
- `/e status` → Change le statut (public/privé).
- `/e list` → Liste des équipages.

:::tip
Toutes les commandes peuvent être abrégées avec `/e`.
:::
