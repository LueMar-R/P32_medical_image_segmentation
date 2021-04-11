# P32_medical_image_segmentation
CNN, U-Net, Semantic Segmentation


__A faire :__<br>
- Augmenter la data à 3000 images (ou plus, la limite, c'est quand ça crash à l'entrainement), en réduisant la taille des images à 256x256 pour pas que ça crashe.
- Améliorer l'algo de Data-Augmentation pour rajouter traitements :
   - voir s'il y a des paramètres pour le skimage.util.random_noise, pour augmenter un peu les effets éventuellement
   - voir s'il peu être interessant de faire des crop.
   - ou éventuellement essayer avec keras plutôt qu'avec Scikit-image
- Voir s'il y des méthodes moins artisanales pour scorer le modèle... (Là c'est du full home-made)
- Commenter le notebook et interpreter les résultats,
- Sortir les prédictions sur le X_test ? (mais quel est l'intérêt vu qu'on a pas les labels ?)
- ...

**Reste aussi à faire :** (demandé dans le brief)<br>
`Expliquer le choix de l'architecture utilisée dans le modèle.`<br>
`Afficher la courbe de la fonction loss (Entraînement et validation), la courbe de l'accuracy du modèle (demandé dnas le brief)`<br>
--> ajouter accuracy aux metrics de l'entrainement .fit pour pouvoir tracer la courbe






______
_Pour utiliser le notebook sur colab :_<br>
_Créez un dossier `P32_medical_image_segmentation` à la racine de votre Google Drive_<br>
_Copiez-y le fichier data_seg.zip_<br>
_Synchronisez. C'est tout._
