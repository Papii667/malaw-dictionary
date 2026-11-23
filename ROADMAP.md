# Roadmap de Malaw

Malaw est un clavier Android pour le terminal et la cybersécurité, basé sur HeliBoard.

## Phase 0 : dictionnaire (terminé)
- [x] Dépôt malaw-dictionary en ligne
- [x] Dictionnaire en trois niveaux de priorité (basiques, outils de sécurité, autres)
- [x] Retrait des mots réservés du shell
- [x] Identité visuelle : signature et maquette
- [ ] Script build.sh pour régénérer le dictionnaire

## Phase 1 : le fork qui compile
- [ ] Fork malaw-keyboard à partir de HeliBoard
- [ ] Activation de GitHub Actions et première compilation
- [ ] Nom, icône et applicationId
- [ ] Crédits à HeliBoard dans le README

## Phase 2 : l'identité de Malaw
- [ ] Thème par défaut : fond sombre, accent violet, signature Malaw
- [ ] Rangée de touches terminal : Ctrl, Esc, Tab, flèches, | ~ / -
- [ ] Passage automatique sur Malaw dans Termux
- [ ] Dictionnaire intégré dans l'APK

## Phase 3 : les suggestions intelligentes
- [ ] Classement strict : les mots qui commencent par la lettre tapée d'abord, puis les basiques avant les outils
- [ ] Malaw Assist : correction des commandes mal tapées, avec interrupteur et trois niveaux (désactivé, suggestions seulement, correction automatique)
- [ ] Options et sous-commandes (-sV, --script...), si le format le permet
- [ ] Courte description de chaque commande, pour les débutants

## Phase 4 : la publication
- [ ] README complet avec captures et vidéo
- [ ] Première release APK sur GitHub
- [ ] Annonce sur X
