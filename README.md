# TP2_Reseau
Travail pratique numéro 2 pour le cours de Réseau

## section 1


## section 2


## Question 0


## Question 1
Pour les adresses suivantes indiquez:

1. leur classe;
2. la partie réseau et la partie hôte;
3. si ce sont des adresses privées ou publiques.

---> **192.168.1.1** : C / réseau : 192.168.1 hôte : 1 / privée

---> **172.16.254.1** : <mark>B</mark> / réseau : 172.16 hôte : 254.1 / privée

---> **10.0.0.1** : A / réseau : 10 hôte : 0.0.1 / privée

---> **203.0.113.45** : C / réseau : 203.0.113 hôte : 45 / publique

---> **169.254.123.78** : B / réseau : 169.254 hôte : 123.78 / publique

---> **8.8.8.8** : A / réseau : 8 hôte : 8.8.8 / publique


## Question 2 
1.	Définir l’adresse de diffusion « broadcast ».
    - L’adresse de diffusion « broadcast » est la dernière adresse d’un sous-réseau qui permet de communiquer à tous les hôtes.
2.	Quelle est l’opération effectuée sur une adresse pour déterminer l’adresse de réseau ?
    - Pour déterminer l’adresse réseau, on fait une opération ET Logique en binaire entre le masque et l’adresse IP.  
3.	Soit l’adresse IP 197.2.0.0. On souhaite définir 8 sous-réseaux.
    - 197.2.0.0 : Classe C, masque 255.255.255.0/24
    - 2^<mark>3</mark> = 8 (sous réseaux)
    - masque décimal pointé : 24 + 3 = 27 bits à 1 : 11111111 11111111 11111111 11100000 --> 255.255.255.224
    - Notation CIDR : 27 bits à 1 --­> /27
    - Incrémentation : 256 - 224 = 32
      
    Sous réseau 1 : **197.2.0.0/27**
    Sous réseau 2 : **197.2.0.32/27**
    Sous réseau 3 : **197.2.0.64/27**
    Sous réseau 4 : **197.2.0.96/27**
    Sous réseau 5 : **197.2.0.128/27**
    Sous réseau 6 : **197.2.0.160/27**
    Sous réseau 7 : **197.2.0.192/27**
    Sous réseau 8 : **197.2.0.224/27**






