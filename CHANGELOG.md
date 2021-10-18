# Changelog

Journal des modifications du logiciel de configuration SmartVOX®

## 1.3.0 - 2021-10-18

### Added

- Windows/Linux: Barre de titre personnalisée, avec le logo, le nom de l'application et la version
- Windows/Linux: Affichage d'une fenêtre de chargement au démarrage de l'application
- Affichage d'un popup pour lister les SmartVOX appairés en Bluetooth
- Affichage d'un popup lorsque la connexion à un SmartVOX est impossible. Listing des causes potentielles, et actions possibles
- Connexion directe à la SmartREMOTE-1 depuis l'écran d'acceuil (si branché). Affichage d'un popup si le câble n'est pas branché

### Changed

- Nombreuses améliorations visuelles et ergonomiques
- Amélioration de la visualisation/configuration d'un scenario (entrée pour SmartVOX / bouton pour SmartREMOTE-1)
- Amélioration du processus pour ajouter un son personnalisé. Désormais, il y a un bouton d'ajout de son pour chaque emplacement vide
- Amélioration de l'affichage des informations en mode Expert
- Amélioration de la gestion d'erreurs lorsque le son à déployer n'est pas valide
- Amélioration de la gestion d'erreurs pour les chaînes de caractères (nom de l'appareil, nom des groupes, clé d'encryptage)
- Refonte globale du code de l'application (interne) pour de meilleurs performances

### Fixed

- Icône de l'application (fix #2)
- Blocage lors du transfert de fichiers audio (fix #3)
- Blocage lors d'une mise à jour firmware (fix #4)
- Bouton de déconnexion non fonctionnel après mise à jour firmware (fix #6)
- Windows: Affichage des SmartVOX non appairés (fix #7)
- Blocage lors de l'application des modifications (fix #8)
- Impossibilité de modifier la durée du son du scenario SmartREMOTE-1 (fix #9)
- Windows: Signature de l'application (fix #11)
- Sauvegarde du dernier dossier lors de transferts consécutifs de sons personnalisés (fix #13)
- Corrections de textes et traductions
- Windows/Linux: Correction des problèmes de connexion/déconnexion Bluetooth

## 1.2.2 - 2021-03-12

### Fixed

- Version mobile : l'application ne se lançait pas (écran blanc au démarrage)

## 1.2.1 - 2021-03-09

### Added

- SmartVOX : Paramétrage du volume sonore des sons système (mélodie de démarrage, bip défaut, message de connexion/déconnexion Bluetooth)
- Affichage période max du rafraichissement du Watchdog en mode Expert
- Version mobile : Ajout d'un bouton pour afficher les paramètres Bluetooth du téléphone afin de s'appairer. Lors du rebasculement vers l'appli mise en arrière-plan, scan automatique pour voir le smartVOX ajouté/supprimé

### Fixed

- SmartREMOTE-1 : désactivation du son 2 non pris en compte
- SmartVOX: Problème d'affichage de la page de supervision en mode Expert
- Problème de gestion des noms de fichier audio lors du transfert
- Version mobile : sous Android v6, la fenêtre de sélection pour charger un firmware ne s'ouvrait pas
- Correction textes : "[Défaut] Alimentation secteur [OK]" + "[Défaut] Batterie de secours [OK]"

## 1.2.0 - 2020-11-17

### Added

- Gestion de la configuration de la télécommande SmartREMOTE-1
- Vérification de la validité du fichier audio avant transfert (format WAV PCM 16bits 48kHz)

### Fixed

- Correction mineures d'affichage
- Amélioration de la stabilité globale de l'application

## 1.1.0 - 2020-10-23

### Added

- Possibilité d'annuler le transfert d'un fichier son

### Changed

- Améliorations affichage de la configuration des entrées
- Masquage d'un appareil distant lorsque le type d'appareil n'est pas un SmartVOX®
- Gestion de la déconnexion lors d'un problème de transmission Bluetooth

### Fixed

- Correction problèmes d'affichage en version mobile

## 1.0.1 - 2020-09-03

### Changed

- Amélioration de la stabilité de la connexion Bluetooth

### Fixed

- Gestion de la connexion en version mobile
- Correction affichage d'icônes et textes

## 1.0.0 - 2020-08-07

### Added

- Première version stable du logiciel de configuration SmartVOX®
