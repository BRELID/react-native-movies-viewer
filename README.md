# Movies viewer with React Native

1) `npm install` in the root directory

2) Add your api key in /API/TMDBApi.js -> const API_TOKEN (https://www.themoviedb.org for a key api)

## How to use with android emulator

### On Windows 10

1) Add theses paths in your environnements variables (system and user):
> C:\Users\YOUR_USER_NAME\AppData\Local\Android\Sdk\platform-tools  
> C:\Users\YOUR_USER_NAME\AppData\Local\Android\Sdk\emulator  
> C:\Users\YOUR_USER_NAME\AppData\Local\Android\Sdk\tools\bin  

2) Launch this command on a terminal
> adb devices  

(or kill and relaunch adb kill-server)  

3) Launch your android studio and your virtual android device

4) Launch your project  
> expo start --android  

5) Accept exterior app in your virtual android device for install expo (first time only)  

6) Choose launch on android emulator on your navigator in metro

7) Done, enjoy !


### On mac OS

1) On terminal, enter this command:
> cd /Users/YOUR_NAME/Library/Android/sdk/platform-tools/  

2) Then this one:
> ./adb devices  

(or kill and relanch ./adb kill-server)  

3) And continue steps same on windows at step 3


***
** FR
***

1) Faire un `npm install` dans le dossier racine du projet

2) Ajouter votre clé d'api dans le fichier /API/TMDBApi.js -> const API_TOKEN (https://www.themoviedb.org pour avoir une clé)

### Sur Windows 10

1) Ajouter ces variables d'environnements (dans system et user):
> C:\Users\VOTRE_NOM_UTILISATEUR\AppData\Local\Android\Sdk\platform-tools  
> C:\Users\VOTRE_NOM_UTILISATEUR\AppData\Local\Android\Sdk\emulator  
> C:\Users\VOTRE_NOM_UTILISATEUR\AppData\Local\Android\Sdk\tools\bin  

2) Lancer cette commande dans un terminal
> adb devices  

(ou tuer le processus avec la commande : adb kill-server)  

3) Lancer android studio et une machine virtuelle android

4) Lancer votre projet 
> expo start --android  

5) Accepter de lancer des applications extérieurs dans votre emulateur pour pouvoir installer expo (seulement la première fois)  

6) Choisir dans votre navigateur dans metro : launch on android emulator  

7) Terminé !


### Sur mac OS

1) Dans un terminal, entrer la commande :
> cd /Users/YOUR_NAME/Library/Android/sdk/platform-tools/  

2) ensuite la commande :
> ./adb devices  

(ou tuer le processus avec la commande : adb kill-server)  

3) Continuer avec les mêmes étapes sur windows à partir de l'étape 3
