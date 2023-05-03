# Unicorn365
Langage simple et compilateur pour créer rapidement des apps web et mobile en lien avec différentes technos (IA, ERP, IOT, SMS, ...)

Très simple à utiliser, **vous pouvez coder dans n'importe quel éditeur** : Visual Studio Code, Notepad++, ...
Nous avons un exemple avec Notepad++ et la coloration syntaxique adaptée au langage Unicorn365.

Il suffit d'appeler le compilateur avec la syntaxe suivante : 
**Unicorn365.exe <yourprojectname.prj>** pour générer les fichiers contenant votre app web/mobile et la diffuser directement sur votre serveur web pour la tester.

**Votre fichier projet (.prj) doit être sous la forme :**
deployserver=Nom du serveur sftp pour déployer l'app web/mobile sur votre serveur web (voir Unicorn365 /addserver <yourserverfile.srv>)
mainprogram=main.Unicorn
source=client.Unicorn
source=contact.Unicorn
resourcespath=\projects\mainhelloworld\


