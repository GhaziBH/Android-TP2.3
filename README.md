# Android-TP2.3 Travail à faire
Question 1:
Q:Quelle méthode de constructeur utilisez-vous pour créer une intention implicite de lancer une application de caméra?

R:new Intent(String action)

Question 2:
Q:Lorsque vous créez un objet Intention implicite, lequel des énoncés suivants est vrai?

R:Résolvez l'intention avec le système avant d'appeler startActivity() ou startActivityforResult().

Question 3:
Q:Quelle action Intention utilisez-vous pour prendre une photo avec une application appareil photo? 

R:Intent takePicture = new Intent(MediaStore.ACTION_IMAGE_CAPTURE);
