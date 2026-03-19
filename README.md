# Github - Commande et gestion

# 1️⃣ Les branch :

Le github est séparé en plusieurs branches :
- [main](https://github.com/ewanlenogue/Agile_GRP_3)
- [sprint1](https://github.com/ewanlenogue/Agile_GRP_3/tree/sprint1)
- [sprint2](https://github.com/ewanlenogue/Agile_GRP_3/tree/sprint2)
- [sprint3](https://github.com/ewanlenogue/Agile_GRP_3/tree/sprint3)

La branch main represente la version la plus abouti du projet

Les branch des sprint ne sont plus modifiable a la fin de son sprint associé

# 2️⃣ Les commandes utiles :

Ajout du repo distant :
```
git clone git@github.com:ewanlenogue/Agile_GRP_3.git

git checkout sprint1
git checkout sprint2
git checkout sprint3

```

Pour changer de branch
```
git checkout nom_branch
```

Mettre a jour le depot
```
# Se placer sur main
git checkout main

# Fusionner sprint1
git merge sprint1

# Pousser les changements sur GitHub
git push
```


# TP Agile - Déploiement Kubernetes

# 1️⃣ Répartition des rôles : 

- 🧑‍💼 Product Owner (PO) : Florent
- 🧑‍🔧 Scrum Master (SM) : Ewan
- 👨‍💻 Dev Team : Ismaël et Ariel 

# 2️⃣ Promox Indication :

- 🏷️ Tag View : agilegrp3
- 🖥️ VM ID : 3210 --> 3213
- 🌐 Adressage : 172.16.130.60 --> 172.16.130.63
- 🔀 Gateway : 172.16.255.254
- 🖋️ Nommage : \<Fonction_VM>\-GRP-3


```
```