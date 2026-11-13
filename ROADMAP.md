# Fritkot Tycoon 3D : feuille de route

Mise à jour à chaque version. ✅ = fait et testé · 🔧 = à corriger · 🔜 = prochaine étape · 💡 = idée.

## ✅ Terminé
### Base et sauvegarde
- ✅ Jeu PWA installable, hors ligne (sw.js), mises à jour automatiques avec message.
- ✅ Sauvegarde automatique (`fritkot-save`), copie de secours (`fritkot-bak`), copie d'avant (`fritkot-prev`), code d'export/import.
- ✅ Conversion des vieilles sauvegardes (`migrate`) : testée à chaque ajout de champ.
### Monde 3D
- ✅ Grand-Place 3D réaliste (textures photo Poly Haven, modèles 3D), hôtel de ville, église, fontaine, arbres, lampadaires.
- ✅ Cycle jour/nuit (ciel physique, éclairage, fenêtres allumées), météo (soleil, nuages, pluie, froid, canicule, neige) sur l'éclairage et le brouillard.
- ✅ Vrais personnages animés (Quaternius) : marcher, courir, attendre, téléphoner, servir, manger.
- ✅ Passants, file de clients réelle devant la baraque, voiture qui circule.
- ✅ Intérieurs : friterie (selon le local), bureaux (banque, commune, AFSCA…), grossiste.
- ✅ Vapeur des friteuses et du toit de la baraque.
- ✅ Nourriture 3D détaillée (frites, sauces, fricadelle, fricadelle spéciale, mitraillette, burger, canettes) + images dans l'interface.
### Jeu
- ✅ Gestion : prix, stock, graisse, propreté, qualité, réputation, AFSCA, démarches (BCE, AFSCA, commune, assurance).
- ✅ Économie belge : TVA, cotisations, impôt, électricité, loyer, assurances, comptable, prêt, vie privée.
- ✅ Personnel (CP 302), CV et entretiens, motivation, absences, rapports, décisions du patron.
- ✅ 4 locaux : baraque → friterie en dur → centre-ville → brasserie-friterie.
- ✅ Matériel (friteuses 1-4 bacs, éplucheuse, frigo, hotte…), publicité, événements (Diables Rouges, kermesse, travaux…).
- ✅ Moi-même en 3D : servir au comptoir, fournée (zone dorée), nettoyer, changer la graisse, porter la marchandise.
- ✅ Clients avec personnalités au comptoir (habitué, pressé, étudiant, famille, touriste, ouvrier, critique) et jauge de patience.
- ✅ Produits à débloquer : mitraillette, fricadelle spéciale, burger maison.
- ✅ Succès (objectifs) et journal.
### Lot 3 (version 2026-11-13.13)
- ✅ Cuisine étape par étape : frites au chaud après chaque fournée, plancha avec 2 faces à retourner (risque de brûler), panier qui plonge dans l'huile, steaks qui changent de couleur, vapeur.
- ✅ Il faut des frites prêtes et des steaks grillés pour servir au comptoir.
- ✅ Clients fidèles : ils se souviennent (visites, satisfaction), reviennent, attirent plus de clients ; liste dans 📊 Gestion.
- ✅ Monde vivant : pluie et neige visibles, 4 voitures qui circulent, clients qui s'impatientent (téléphone, bras croisés), décorations de Noël (guirlande qui clignote, sapin).
- ✅ Personnalisation : couleurs du fritkot, uniformes du personnel, lumière de l'enseigne.
- ✅ Économie : 3 fournisseurs (discount, horeca, producteurs locaux), formations du personnel.
- ✅ Sons : friteuse qui crépite, rue, pluie, foule, caisse, petite valse musette générée (réglable).
### Lot 4 (version 2026-11-13.14)
- ✅ Défis du jour (3 par jour d'ouverture, récompenses, bonus et série de jours).
- ✅ Avis Google fictifs selon la qualité, l'attente, les prix et la propreté ; la note moyenne influence le nombre de clients.
- ✅ Pannes de machines (friteuse, frigo, terminal, hotte) : réparateur ou réparation soi-même en 3D (animation à genoux, 65 % de réussite) ; contrat d'entretien ; fumée noire au-dessus de la friteuse en panne.
- ✅ Clients qui mangent sur place (terrasse ou mange-debout) avant de repartir.
- ✅ Zoom de la caméra (pincer à deux doigts, molette).
- ✅ Plateau qui se garnit sur le comptoir pendant qu'on compose la commande.
### Lot 5 (version 2026-11-13.15)
- ✅ Clients difficiles (avis sévères) et généreux (gros pourboires) ; budget par client (trop cher = mécontent, avis).
- ✅ Enfants avec certains clients dans la file (plus petits, animés).
- ✅ File plus espacée (les clients ne se chevauchent plus).
### Lot visuel (version 2026-11-13.16) — inspiré des photos du joueur
- ✅ Cuisine pro : carrelage métro blanc brillant, sol en carreaux orange, inox brossé, comptoir inox avec bandeau de couleur, lampes industrielles suspendues, spot chaud avec ombres.
- ✅ Objets réels : écran des commandes (mis à jour en direct), flacons de sauce, bacs d'ingrédients (salade, tomates, cheddar, oignons), planche à découper, casserole, caisses de pommes de terre, bidon d'huile, extincteur, tabourets, poster.
- ✅ Guirlande d'ampoules chaudes sous l'auvent (le soir), personnel en casquette aux couleurs choisies.

## 🔧 À corriger / surveiller
- 🔧 Avertissement three.js « Texture marked for update but no image data » (existant, sans effet visible).
- 🔧 Avertissement « parameter 'color' undefined » dans le grossiste (existant, sans effet visible).
- 🔧 Vêtements peints sur les corps : un peu moulants (prévoir de vrais vêtements 3D).
- 🔧 Éblouissement encore un peu fort au centre de la baraque la nuit.
- 🔧 Écart avec les photos (jeux PC sur moteur Unreal) : continuer pièce par pièce (vrais vêtements, visages, objets de cuisine 3D sur mesure).
- 🔧 Tester les performances sur un vrai téléphone Android d'entrée de gamme.

## 🔜 Prochaines étapes (ordre prévu)
1. Préparation encore plus visuelle : sauce versée, pain de mitraillette garni, emballage.
2. Tables, chaises et décoration à placer ; panneaux publicitaires ; nouveaux styles de fritkot.
3. Employés autonomes visibles en 3D (ils servent, cuisent, nettoient) avec fatigue et efficacité.
4. Mode paysage ; écran de chargement soigné ; tutoriel guidé.
5. Deuxième établissement, puis chaîne belge.

## 💡 Plus tard
- Tables et chaises à placer, décoration intérieure, panneaux publicitaires.
- Livraison, deuxième établissement, chaîne belge, franchises.
- Radio avec plusieurs stations.
- Animaux (chiens, pigeons) et petits événements de rue (marché, brocante, carnaval).
- Vrais vêtements 3D, expressions du visage.
