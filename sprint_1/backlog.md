# Sprint Backlog – Sprint n°1

## Objectif du sprint
Mettre en place l’infrastructure de base pour l’hébergement de l’application avec Kubernetes et NFS, et préparer la conteneurisation des services.

---

## Stories et tâches

### 1. Installation de trois serveurs Debian
**Story:** En tant qu’administrateur, je veux installer trois serveurs Debian pour disposer de l’infrastructure de base.  

| Tâche | Description | Statut |
|-------|------------|--------|
| Créer les trois machines virtuelles | Déployer trois VM via l’hyperviseur | À faire |
| Configurer les ressources de base | CPU, RAM, stockage | À faire |
| Paramétrer le réseau et les adresses IP | Configurer IP statiques et routes | À faire |
| Installer les mises à jour et vérifier l’accessibilité | Apt update/upgrade et ping test | À faire |

---

### 2. Installation d’un serveur Kubernetes de type control-plane
**Story:** En tant qu’administrateur, je veux installer un serveur Kubernetes principal pour gérer le cluster.  

| Tâche | Description | Statut |
|-------|------------|--------|
| Installer les composants du nœud principal | kubeadm, kubelet, kubectl | À faire |
| Initialiser le cluster | kubeadm init et configuration kubeconfig | À faire |
| Vérifier le bon démarrage du control-plane | Vérification pods kube-system | À faire |

---

### 3. Installation d’un serveur Kubernetes de type agent
**Story:** En tant qu’administrateur, je veux installer un serveur Kubernetes agent pour exécuter les workloads.  

| Tâche | Description | Statut |
|-------|------------|--------|
| Préparer la machine worker | Mise à jour, prérequis | À faire |
| Installer les composants nécessaires | kubeadm, kubelet, kubectl | À faire |
| Joindre l’agent au cluster | kubeadm join | À faire |
| Vérifier son état depuis le control-plane | kubectl get nodes | À faire |

---

### 4. Installation d’un serveur NFS pour le stockage
**Story:** En tant qu’administrateur, je veux installer un serveur NFS pour partager le stockage entre les nodes.  

| Tâche | Description | Statut |
|-------|------------|--------|
| Installer le service NFS | apt install nfs-kernel-server | À faire |
| Créer le partage de stockage | Définir les répertoires exportés | À faire |
| Tester l’accès au partage | Montage depuis les autres serveurs | À faire |

---

### 5. Préparation de la conteneurisation de l’application et des services
**Story:** En tant que développeur, je veux préparer la conteneurisation pour faciliter le déploiement sur Kubernetes.  

| Tâche | Description | Statut |
|-------|------------|--------|
| Identifier les services à héberger | Lister les services principaux | À faire |
| Préparer les premiers conteneurs ou fichiers de configuration | Dockerfile, docker-compose.yml | À faire |
| Tester une première base d’hébergement | Déploiement test sur un conteneur | À faire |