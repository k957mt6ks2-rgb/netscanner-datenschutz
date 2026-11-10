---
title: Politique de confidentialité – NetScanner
---

# Politique de confidentialité – NetScanner (iPhone, iPad et Mac)

*Ceci est une traduction de l’original allemand, [Datenschutzerklärung](datenschutz). En cas de doute, la version allemande prévaut.*

Dernière mise à jour : 10 novembre 2026

## 1. Responsable du traitement

Sascha Z.
Wilhelmhofallee 68, 47799 Krefeld, Allemagne
E-mail : app.sascha@icloud.com

## 2. Principe

NetScanner ne collecte, ne mémorise et ne transmet aucune donnée à caractère personnel au développeur.
Il n’existe ni compte utilisateur, ni publicité, ni suivi (tracking), ni service d’analyse ou de rapport
de plantage de tiers. Tous les résultats d’un scan réseau restent sur votre appareil.

## 3. Ce que l’app traite sur votre appareil

- **Scan réseau :** adresses IP, noms d’hôte, temps de réponse, ports ouverts, adresses MAC et
  informations sur les fabricants des appareils de votre réseau local. Les données sont conservées en
  mémoire pour l’affichage. En outre, l’app crée après un scan une entrée dans l’historique des scans
  (voir ci-dessous). Si vous exportez des résultats (CSV, PDF ou JSON), vous décidez où le fichier est
  envoyé.
- **Historique des scans et « Mes appareils » :** après chaque scan, l’app mémorise sur votre appareil
  quels appareils (adresse IP, adresse MAC, nom, fabricant) ont été trouvés dans quel réseau et à quel
  moment, afin de pouvoir détecter les appareils nouveaux et manquants. S’y ajoutent les titres, les
  notes et les marquages (« épinglé », « appareil connu ») ainsi que les noms d’appareils et notes
  personnalisés que vous saisissez vous-même. Pour chaque réseau, les 50 derniers scans sont conservés,
  200 au maximum au total ; les scans épinglés sont toujours conservés. Les données se trouvent
  uniquement dans le dossier protégé de l’app sur votre appareil (pas de synchronisation iCloud, pas de
  transmission). Vous pouvez supprimer dans l’app des scans individuels, l’historique d’un réseau et des
  entrées d’appareils ; la suppression de l’app efface toutes les données.
- **Réseau local :** l’app a besoin de l’autorisation « Réseau local » (iOS ou macOS) pour trouver les
  appareils de votre réseau domestique. Le scan envoie des requêtes ping, TCP et UDP (par exemple mDNS,
  NetBIOS, SSDP) à des adresses de votre propre réseau afin de trouver les appareils actifs, leurs noms
  et leurs fabricants. Ces requêtes ne quittent pas votre réseau.
- **Outils réseau :** ping, recherche DNS, traceroute (également via IPv6), vérification de ports,
  vérification web, vérification e-mail, navigateur Bonjour, Wake-on-LAN, calculateur de sous-réseau,
  test de débit et « IP publique » ne s’exécutent que lorsque vous les lancez. Leurs résultats (par
  exemple temps de réponse, route, certificat, ports) ne sont conservés en mémoire que pour l’affichage.
  Le test de débit fait exception : l’app mémorise ses résultats (date et heure, téléchargement,
  envoi, latence, type de connexion, emplacement du serveur de mesure) sous forme d’historique des tests
  de débit sur votre appareil (jusqu’à 200 entrées, supprimables une par une ou en totalité), ainsi que
  l’affichage choisi (compteur ou barres).
- **Widgets et contrôles (iPhone et iPad) :** le widget réseau et le widget de test de débit affichent
  la dernière adresse IP publique connue, la date et l’heure ainsi que le nombre d’appareils du dernier
  scan, de même que la dernière mesure du test de débit. Pour cela, l’app dépose ces valeurs dans un
  fichier du dossier partagé (groupe d’apps) de l’app et du widget sur votre appareil. Les autres apps
  n’y ont pas accès. Les contrôles du Centre de contrôle ne font qu’ouvrir l’app. La section 4 décrit
  comment les widgets envoient des requêtes vers Internet.
- **Siri et Raccourcis :** les actions de l’app (par exemple scan, ping, test de débit, traceroute,
  IP publique) s’exécutent sur votre appareil. L’app en renvoie le résultat à Siri ou à l’app
  Raccourcis ; ce que vous en faites ensuite relève de votre décision.
- **Informations Wi-Fi et localisation (iPhone, iPad et Mac) :** pour afficher le nom du Wi-Fi et la
  qualité de la connexion, le système (iOS ou macOS) exige l’autorisation « Localisation » (Lorsque
  l’app est active). L’app ne lit pas de coordonnées de localisation et ne mémorise ni ne transmet
  aucune position.
- **Accès au routeur (facultatif, iPhone, iPad et Mac) :** si vous saisissez l’adresse, le nom
  d’utilisateur et le mot de passe de votre routeur, l’app lit la liste des appareils directement depuis
  votre routeur. Les identifiants ne sont stockés que sur votre appareil (mots de passe dans le
  trousseau d’iOS ou de macOS) et ne sont envoyés qu’à votre propre routeur.
- **Version Mac :** l’app Mac offre les mêmes fonctions que l’app iPhone et iPad (scan réseau, outils
  réseau, affichage Wi-Fi, accès au routeur) sans widgets, mais avec une entrée dans la barre des menus
  qui affiche l’adresse IP publique, le dernier scan et des actions rapides. Lorsque vous l’ouvrez,
  l’app interroge l’adresse IP publique (voir section 4). Sur demande, l’app démarre à l’ouverture de
  session (interrupteur dans l’entrée de la barre des menus ; macOS la répertorie alors sous « Éléments
  de connexion », où vous pouvez la désactiver à tout moment) et continue de fonctionner en arrière-plan
  afin que l’entrée de la barre des menus reste visible. L’app s’exécute dans le bac à sable (App
  Sandbox) de macOS. Elle détermine les adresses MAC à partir de Bonjour, UPnP, NetBIOS ou de la liste
  des appareils du routeur ; elle ne lit pas la table ARP du Mac.

## 4. Requêtes auprès de services externes

Pour les fonctions « IP publique » (y compris l’affichage du fournisseur) et « Test de débit » ainsi que
pour les widgets, l’app envoie des requêtes à des services sur Internet. Pour des raisons techniques, ces
services voient votre adresse IP publique :

| Service | Finalité |
|---|---|
| ipify.org (api.ipify.org, api6.ipify.org) | Détermination de votre adresse IPv4/IPv6 publique |
| ipwho.is, à défaut ipinfo.io | Attribution de l’IP publique à un fournisseur (FAI), à un numéro AS et à une localisation approximative |
| Measurement Lab (M-Lab) : locate.measurementlab.net et le serveur de mesure qui en est attribué | Test de débit : recherche du serveur le plus proche, puis mesure du téléchargement, de l’envoi et de la latence avec le test ouvert NDT7 |

Ces requêtes sont déclenchées lorsque vous ouvrez ou actualisez l’outil « IP publique » (également via
le bouton d’actualisation du widget réseau ou en ouvrant l’entrée de la barre des menus sur le Mac), ou
lorsque vous touchez « Démarrer » dans le test de débit ou « Lancer le test » dans le widget de test de
débit. **Exception, widget réseau :** tant que vous avez configuré le widget réseau sur l’écran
d’accueil, l’écran verrouillé ou dans la vue Aujourd’hui, il interroge, même sans que l’app soit
ouverte, environ toutes les 30 minutes (iOS détermine l’heure exacte) votre adresse IPv4 publique
auprès d’ipify.org afin de l’afficher à jour. Cette requête en arrière-plan n’est adressée qu’à
ipify.org, et non à ipwho.is, ipinfo.io ou Measurement Lab. Elle prend fin lorsque vous supprimez le
widget. Aucune autre donnée (nom, identifiant d’appareil, données réseau) n’est transmise. Les services
sont exploités par des tiers. Leurs propres politiques de confidentialité s’appliquent à leur traitement
des données.

**Test de débit et Measurement Lab :** un test de débit transfère des données de test pendant environ
10 secondes en téléchargement et autant en envoi. Selon votre connexion, cela représente plusieurs
centaines de mégaoctets ; sur le réseau mobile, cela peut entamer votre forfait de données. Selon sa
propre politique de confidentialité, Measurement Lab conserve les résultats de ses mesures sans limite
de durée et les met à disposition du public sous forme de données de recherche ouvertes. Cela comprend
votre adresse IP ainsi que la date et l’heure de la mesure. Le test de débit ne démarre que lorsque vous
touchez ou cliquez sur « Démarrer », ou touchez « Lancer le test » dans le widget de test de débit, et
l’app signale cette publication dans la fenêtre du test de débit. Le widget de test de débit exécute la
même mesure ; il ne la démarre jamais de lui-même. Si vous ne le souhaitez pas, ne lancez pas le test
de débit. Vous trouverez des précisions et des informations sur l’exercice de vos droits à l’adresse
<https://www.measurementlab.net/privacy/>.

**Ping, recherche DNS, traceroute, vérification de ports, vérification web et vérification e-mail :**
avec ces outils, l’app envoie des requêtes à la cible que vous saisissez (pour la vérification web, elle
établit une connexion et lit le certificat TLS et les en-têtes HTTP) ainsi que, pour le traceroute, aux
routeurs situés sur le chemin. La résolution de noms est assurée par le serveur DNS de votre réseau. Ces
requêtes vont directement de votre appareil à la cible concernée et non au développeur.

**Vérification e-mail :** l’app interroge les enregistrements DNS du domaine que vous saisissez (MX, SPF,
DKIM, DMARC, MTA-STS, TLS-RPT et BIMI). Ces requêtes passent par le serveur DNS de votre réseau, qui
peut les voir, et le développeur ne peut pas les consulter. Si le domaine possède une politique MTA-STS,
l’app la télécharge en HTTPS à l’adresse `mta-sts.<domaine>` du domaine saisi. Aucune autre donnée n’est
transmise, et les résultats ne sont conservés en mémoire que pour l’affichage.

La base juridique est l’art. 6, par. 1, point b) du RGPD (fourniture de la fonction que vous avez
appelée ou configurée, par exemple le widget).

## 5. Pas de divulgation, pas de suivi

Le développeur ne reçoit aucune donnée de l’app. Il n’y a pas de suivi au sens de l’App Tracking
Transparency d’Apple.

## 6. Vos droits

Le développeur ne traitant aucune donnée à caractère personnel, il ne peut pas vous fournir
d’informations à ce sujet. Vous pouvez à tout moment révoquer les autorisations accordées dans les
réglages d’iOS ou de macOS et supprimer l’app, ce qui efface toutes les données stockées localement.
Vous disposez des droits prévus par le RGPD (accès, rectification, effacement, limitation, opposition,
réclamation auprès d’une autorité de contrôle).

## 7. Modifications

Si l’app est étendue par des fonctions qui transmettent des données, la présente politique sera adaptée
au préalable.

## 8. Mentions légales

Identification de l’éditeur : [Mentions légales](impressum-fr).
