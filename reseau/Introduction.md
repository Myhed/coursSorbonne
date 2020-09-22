# Introduction aux réseau

## Reseau de petite taille

* **LAN**  ___(Local Area Network)___
* **WLAN** ___(Wireless local Network)___
* **PAN**  ___(Personal Area Network)___
* **BAN** ___(Body Area Network)___

## Reseau de grande taille

* **WAN** ___(Wide Area Network)___

## Interconnexion des reseau

Il y'a différents type de reseaux

* **Internet** <=> Regroupe l'ensemble des noeuds pour communiquer sur différents réseau distant
* **Intranet** <=> Un Reseau interne local.
* **Extranet** <=> Un Reseau permettant de se connecter à un réseau intranet à distance.

## Modèle de communication

* **Peer to Peer**
* **Client-Server**

Les communication se fait par l'intermédiaire de la couche ___transport___ **TCP/UDP** lors de l'utilisation d'un service applicatif tel que **HTTP, SSH,SMTP etc..***

## Fiabilité des communications

il y'a deux types de communications

* **Sans connexion <=>** ___UPD___
    * ___Aucune numérotation des paquets et peut avoir une perte de paquet___
        * **la Video, Audio <=>** est préférable d'utiliser cette méthode de transmission
* **Avec connexion <=>** __TCP__
    * ___Numérotation des paquets dans un certaine ordre permet une connexion plus stable mais plus lourd, il assure que tout les paquets sont transmis lors d'une communucation___


