Using:
+ MPLAB IDE 3.60
+ XC8 v1.41
+ MPLAB Code Configurator v3.x

Développer directment sous linux...

On utilise un PIC 16F1455 et un kit ibld.it ($15 sur tindie)

tutorial lié & code source exemple USB HID:
https://www.codeproject.com/Articles/830856/Microchip-PIC-F-USB-Stack
doit compiler avec XC8 v1.35 (au dessus, plus de peripheral libraries!)

- [ ] compiler le code source et vérifier que ca fonctionne (faire un client python qui dialogue en HID)
- [ ] Partir du code source exemple, utiliser Code Configurator pour matcher la configuration, vérifier que ca compile et que ça fonctionne
- [ ] Ajouter une fonctionnalité pour déterminer par exemple la position d'un portard (en utilisant l'ADC), compiler et tester
- [ ] documenter, notamment l'install potentiel de driver (comme pour MUTA operator?)
