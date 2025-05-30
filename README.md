# Linux From Scratch 12.3 – Projet personnel avec systemd

Ce dépôt documente la construction complète d'un système Linux à partir de zéro, en suivant le livre **LFS 12.3** (avec systemd).

Objectif : comprendre en profondeur l'organisation d'un système GNU/Linux, compiler chaque brique à la main, et créer ma propre base système.

---

## Objectifs pédagogiques

- Consolider ma maîtrise de Linux à bas niveau (compilation, arborescence, outils GNU)
- Préparer à la certification **LFCS** (Linux Foundation Certified Sysadmin)
- Me différencier sur le marché en tant qu'admin système / DevOps autonome et rigoureux
- Explorer les possibilités de personnalisation post-LFS (via BLFS ou init system alternatifs)

---

## Environnement

- **Hôte** : Debian 12 (minimal)
- **Méthode** : compilation manuelle en `chroot`
- **Cible** : système LFS stable avec `systemd`
- **Stockage** : partition dédiée montée sur `/mnt/lfs`
- **Utilisateur** : `lfs`

---

## Planning prévisionnel (juin 2025)

| Semaine | Étapes prévues |
|--------:|-----------------------------------------------------|
| S1 | Préparation système hôte + compilation des outils |
| S2 | Construction du système de base (chroot + toolchain)|
| S3 | Configuration finale, boot, systemd |
| S4 | Personnalisation, tests, éventuelle extension BLFS |

---

## Structure du dépôt

```bash
lfs-12.3-systemd/
├── notes/     # Journal de progression et commandes
├── scripts/   # Scripts maison (vérifications, builds…)
├── images/    # Captures d'écran ou diagrammes
├── markdown/  # Fiches explicatives (bash, systemd, make…)
├── README.md  # Ce fichier
```

---

## Journal de progression

Chaque étape clé est documentée dans le dossier `notes/`, incluant :
* Commandes tapées
* Fichiers de conf modifiés
* Explications de chaque outil
* Problèmes rencontrés et solutions

## Pourquoi ce projet ?

Parce que faire un `apt install` c'est simple. Mais **comprendre ce qui se passe en dessous**, ça forge un vrai sysadmin.

LFS, c'est un rite de passage :
* Tu compiles tout toi-même
* Tu choisis ce que contient ton OS
* Tu comprends réellement ce qu'est un système Linux

Et surtout : **tu ne subis plus, tu construis**.

## Liens utiles

* Livre officiel LFS 12.3 (Systemd)
* BLFS (Beyond Linux From Scratch)
* Certification LFCS

## Contact

**[Nom ou pseudo]** – Futur admin système & passionné de Linux  
**[Lien vers ton LinkedIn, portfolio ou blog]**