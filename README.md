# Alcora — versions

Binaires construits d'Alcora, un client de bureau Windows pour visionner les cameras
d'un controleur UniFi Protect. Ce depot ne contient que les paquets publies : le code
source sera publie separement.

## Installer

Telecharger `Alcora-win-Setup.exe` depuis la [derniere version][latest] et le lancer.
L'application s'installe pour l'utilisateur courant, sans droits d'administrateur, et se
met a jour d'elle-meme au lancement.

[latest]: https://github.com/dentalsystems/Alcora-releases/releases/latest

## Signature

Les binaires sont signes par un certificat auto-signe (`CN=Alcora`). Windows ne le connait
pas : il annoncera un editeur inconnu tant que ce certificat n'a pas ete installe sur le
poste. C'est le comportement attendu d'un logiciel qui n'achete pas de certificat commercial.

## Le nom

Alcor est la petite etoile accolee a Mizar, dans la queue de la Grande Ourse. Depuis
l'Antiquite, la distinguer a l'oeil nu sert de test de vue : qui voit Alcor voit net.

Ce projet s'appelait ProtectViewer jusqu'au 28.07.2026. Les versions anterieures a la 2.2.0
portent cet ancien nom et ne recoivent plus de mise a jour.

## Marques

Alcora n'est ni affilie ni approuve par Ubiquiti Inc. « UniFi » et « UniFi Protect » sont
des marques de Ubiquiti Inc.
