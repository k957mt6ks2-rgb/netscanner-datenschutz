---
title: Assistance – NetScanner
---

# Assistance – NetScanner

NetScanner pour iPhone, iPad et Mac. Pour toute question, tout bogue ou toute suggestion, écrivez à
**app.sascha@icloud.com**. Veuillez indiquer l’appareil, la version d’iOS ou de macOS et la version
de l’app (affichée dans l’écran « À propos » de l’app).

Vous trouverez ici la [politique de confidentialité](datenschutz-fr) et les [mentions légales](impressum-fr). (Version allemande : [Support](support).)

## Questions fréquentes

### Le scan ne trouve aucun appareil.
L’app a besoin de l’autorisation **« Réseau local »**. Sans elle, le système rejette les requêtes
vers les appareils de votre réseau domestique. Vérifiez sous *Réglages → Confidentialité et sécurité →
Réseau local* que NetScanner est activé. L’appareil doit en outre se trouver sur le même Wi-Fi que les
appareils que vous recherchez.

### Pourquoi certains appareils sont-ils absents ?
- Les appareils en veille profonde (par exemple les serrures de porte à piles) ne répondent pas et ne
  peuvent donc pas apparaître.
- Les Wi-Fi invités ou IoT se trouvent souvent dans un autre réseau ou sont séparés du réseau principal.
  Leurs appareils ne sont alors pas accessibles depuis le réseau scanné.
- Un scan peut durer plus longtemps, car l’app recherche aussi les appareils qui ne répondent pas au
  ping. Attendez la fin du scan.
- Avec l’accès au routeur (FRITZ!Box uniquement), l’app affiche aussi les appareils de la liste des
  appareils de la box.

### Pourquoi le fabricant est-il absent pour certains appareils ?
Les iPhone, les iPad et de nombreux autres appareils utilisent une adresse Wi-Fi aléatoire (« privée »).
Il n’existe aucune information sur le fabricant pour cette adresse. Si un appareil indique par ailleurs
un nom ou un modèle (par exemple via Bonjour), l’app s’en sert pour faire une attribution. iOS ne
communique pas aux apps les adresses MAC des autres appareils ; l’app les obtient via Bonjour, UPnP,
NetBIOS ou la liste des appareils du routeur.

### Pourquoi l’app a-t-elle besoin de la localisation ?
Uniquement pour que le système communique le **nom et la qualité du signal du Wi-Fi**. L’app ne lit
aucune coordonnée de localisation et ne mémorise ni ne transmet aucune position.

### Que deviennent mes données lors du test de débit ?
Le test de débit utilise le service de mesure ouvert de Measurement Lab (M-Lab). Selon votre connexion,
l’app transfère plusieurs centaines de mégaoctets ; sur les données mobiles, cela peut entamer votre
forfait. M-Lab publie les résultats des mesures, adresse IP comprise, sous forme de données ouvertes. Le
test ne démarre que si vous touchez « Start ».

### Comment fonctionne l’accès au routeur ?
Il est facultatif et destiné aux routeurs FRITZ!Box. Vous saisissez l’adresse, le nom d’utilisateur et le
mot de passe. L’app s’en sert pour lire la liste des appareils directement depuis votre box. Le mot de
passe est stocké dans le trousseau de votre appareil et n’est envoyé qu’à votre propre routeur. L’accès
pour les applications (TR-064) doit être autorisé sur la box.

### L’app plante ou affiche quelque chose d’incorrect.
Veuillez nous indiquer ce que vous avez fait juste avant le plantage. Le rapport de plantage est utile :
*Réglages → Confidentialité et sécurité → Analyse et améliorations → Données d’analyse*, entrée
« NetScanner ».
