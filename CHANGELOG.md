# Bengacoon — journal des versions

## 4.17.4 — 23 septembre 2026
- **Correctif de lancement** : la 4.17.3 se fermait aussitôt ouverte (un défaut d'une bibliothèque d'interface, `androidx.appcompat` 1.7.0, qui empêchait l'écran d'accueil de s'afficher). Une seule ligne change ; ni la logique, ni la base, ni la sauvegarde ne sont touchées.
- Si vous aviez la 4.17.3 : installez ce fichier **par-dessus**, ne désinstallez pas — même signature, vos données du cabinet sont intactes.

## 4.17.3 — septembre 2026
- **Sauvegarde vraiment complète** : la sauvegarde (Réglages ▸ Données ▸ Exports, et la sauvegarde automatique) écrit désormais les 16 tables du cabinet. Elle oubliait les dépenses, les forfaits, la liste d'attente, les devis, les échéances et les indisponibilités.
- La sauvegarde emporte aussi la taille du texte, l'objectif de chiffre d'affaires et le compteur de factures (plus de doublon de numéro après une restauration).
- Une sauvegarde automatique est faite **juste après cette mise à jour** : c'est ce fichier que la génération suivante de Bengacoon (4.18) reprend intégralement.
- **Correctif** : la vérification de mise à jour ne trouvait jamais rien depuis la 4.0 (elle lisait un dépôt privé). Elle lit désormais cette page.

## 4.17.0 — septembre 2026
- Application entièrement traduite en 9 langues (français, anglais, allemand, italien, portugais, espagnol, suédois, norvégien, finnois), aide intégrée comprise.
