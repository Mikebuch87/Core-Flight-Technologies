"Xloader" est un outil d'installation de micrologiciel.

A UTILISER UNIQUEMENT AVEC LES MODULES DE LA MARQUE "CORE FLIGHT TECHNOLOGIES"!!


A quoi il sert?
- Lorsque vous achetez un module de la marque sur le site marchand (https://coreflighttech.com), celui-ci vous est livré avec un micrologiciel compatible uniquement avec MOBIFLIGHT.
  Pour pouvoir utiliser le module avec SPADNEXT et qu'il soit reconnu, vous devrez installer un autre micrologiciel.
  C'est là qu'intervient "Xloader".


Comment faire?
- Fermez toutes les applications
- Connectez votre module via USB
- Exécutez "Xloader.exe"
- Dans la rubrique "Hex file", séléctionnez la version du micrologiciel que vous voulez installer (.hex) en fonction du module concerné (ADF, ATC, COMM ou NAV)
- Dans la rubrique "Device", séléctionnez le dernier choix du menu déroulannt à savoir "EEFIS/NAV/COMM/ATC/ADF V2"
- Dans la rubrique "COM port", séléctionnez le port usb sur leqsuel est connecté le module concerné (!! ne vous trompez pas !!)
- Dans la rubrique "Baud rate", laissez la valeur par défaut qui devrait être "115200"
- Cliquez sur "Upload" et quelques secondes plus tard, un message du style "9534 bytes uploaded" va apparaître
- La mise à jour du micrologiciel est terminée! Vous pouvez quitter "Xloader". Le module sera reconnu et compatbile sur SPADNEXT
