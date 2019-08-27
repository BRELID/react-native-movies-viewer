# Movies viewer with React Native

1) `npm install` in the root directory

2) add your api key in /API/TMDBApi.js -> const API_TOKEN (https://www.themoviedb.org for a key api)

## How to use with android emulator

### On Windows 10

1) add theses paths in your environnements variables (system and user):
> C:\Users\YOUR_NAME\AppData\Local\Android\Sdk\platform-tools  
> C:\Users\YOUR_NAME\AppData\Local\Android\Sdk\emulator  
> C:\Users\YOUR_NAME\AppData\Local\Android\Sdk\tools\bin  

2) launch this command on a terminal
> adb devices  
(or kill and relanch adb kill-server)  

3) launch your android studio and your virtual android device

4) launch your project  
> expo start --android  

5) Accept exterior app in your virtual android device for install expo (first time)  

6) choose launch on android emulator on your navigator in metro

7) Done, enjoy !


### On mac OS

1) on terminal, enter this command:
> cd /Users/YOUR_NAME/Library/Android/sdk/platform-tools/  

2) then this one:
> ./adb devices  
(or kill and relanch ./adb kill-server)  

3) and continue steps same on windows


***
** FR
***

1) faire un `npm install` dans le dossier racine du projet

2) Ajouter votre clé d'api dans le fichier /API/TMDBApi.js -> const API_TOKEN (https://www.themoviedb.org pour avoir une clé)


