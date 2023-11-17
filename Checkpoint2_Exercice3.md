3-1) A est un switch il fait le lien entre tout les ordinateurs et le routeur

3-2) B est un routeur il est la passerelle le réseau 10.10.0.0/16 et 10.12.2.0/24

3-3) ce sonts des interfaces fastethernet et GigabitEthernet 

3-4) Pour PC2 /16 est le masque de sous réseau 

3-5) 10.10.255.254 est sa passerelle par default

3-6) 
PC1 : Adresse de réseau : 10.10.0.0
Première adresse : 10.10.0.1
Dernière adresse : 10.10.255.254
Adresse de broadcast : 10.10.255.255
Nombre d'adresses IP disponibles : 65534

PC2 : Adresse de réseau : 10.11.0.0
Première adresse : 10.11.0.1
Dernière adresse : 10.11.255.254
Adresse de broadcast : 10.11.255.255

PC5 : Adresse de réseau : 10.10.0.0
Première adresse : 10.10.0.1
Dernière adresse : 10.11.255.254
Adresse de broadcast : 10.11.255.255

3-7) le PC1 et le PC5 peuvent communiquer car ils sont sur le meme réseau

3-8) Ils peuvent tous atteindre le Réseau 172.16.5.0/24 sauf le PC 2

3-9) pas d'incidence

3-10) Pour mettre les adresses IP des ordinateurs en dynamique il faudrait rajouter un serveur dhcp entre le routeur et le switch 

3-11) L'adresse MAC est 00 50 79 66 68 00 c'est le pc1

3-12) Oui ça a fonctionné entre PC1 et PC4

3-13) le request correspond a PC1 add MAC:00 50 79 66 68 00 add IP: 10.10.4.1 
Le reply correspond a PC4 add MAC: 00 50 79 66 68 03 add IP: 10.10.4.2

3-14) C'est le protocole ARP il sert a associer une adresse ip à une adresse MAC

3-15) Le materiels A sert a faire la liaison entre PC1 et PC4
Le B ne sert a rien

3.16 Dans cette trame, qui initialise la communication ? Donne l'adresse IP ainsi que le nom du matériel.
C'est PC3 qui initialise la communication 10.10.80.3

3.17 Quel est le protocole encapsulé ? Quel est son rôle ?
C'est le protocole ICMP il sert a vérifier la connexion , et a l'envoi des paquets .

3.18 Est-ce que cette communication a réussi ? Si oui, indique entre quels matériel, si non indique pourquoi cela n'a pas fonctionné.
Non la communication n'as pas fonctionné car les 2 machines ne sont pas sur le meme réseau .

3.19 Explique la ligne du paquet N° 2
le Destinataire du paquets est introuvable , il n'y a pas de communication entre l'expediteur du paquet et le destinataire

3.20 Quels ont été les rôles des matériels A et B ?
Puisque les 2 machines ne communique pas ils n'ont servi a rien .

Q.3.21 Dans cette trame, donne les noms et les adresses IP des matériels sources et destination.
La source :10.10.4.2 est le PC4 
La destination : 172.16.5.253 est g2/0

Q.3.22 Quelles sont les adresses mac source et destination ? Qu'en déduis-tu ?
Src:ca:01:da:d2:00:1c, Dst: ca:03:9e:ef:00:38

Q.3.23 A quel emplacement du réseau a été enregistré cette communication ?
Cette information a été enregistré sur le PC4 
























