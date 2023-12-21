# FCSC 2019 StegCryptoDIY - Final Boss

Comme tout le monde s’en rappelle, Dumb et Dumby ont échangé, il y a quelques semaines, en utilisant un nouveau cryptosystème basé sur les problèmes FACT et DLP : CryptoDIY.

Pour rappel, les paramètres **g_1** et **g_2** sont définis par :

- N = p . q
- g_1 = g^(s_1 . (p - 1)) (mod N)
- g_2 = g^(s_2 . (q - 1)) (mod N) où g est un générateur inconnu, s_1 et s_2 sont deux nonces, et p et q sont inconnus.

Ils pensent avoir une version durcie, montrez leur le contraire en retrouvant leur clé partagée à partir des informations issues des deux challenges précédents StegCrypto DIY - PNG et StegCrypto DIY - RNG !

Note : Cette épreuve avait été proposée lors de la finale du FCSC 2019.

Cette épreuve a été découpée en trois parties :

- [StegCryptoDIY - PNG](README_1_3.md)
- [StegCryptoDIY - RNG](README_2_3.md)
- **StegCryptoDIY - Final Boss**


## Images du challenge

**leHACK19_chall.png**
![leHACK19_chall.png](leHACK19_chall.png)
**leHACK19_ref.png**
![leHACK19_ref.png](leHACK19_ref.png)


Auteur : Guena

Origine : [StegCryptoDIY - Final Boss](https://hackropole.fr/fr/challenges/crypto/fcsc2019-crypto-steg-crypto-diy-3/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2019-crypto-steg-crypto-diy.git

> cd fcsc2019-crypto-steg-crypto-diy


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/crypto/fcsc2019-crypto-steg-crypto-diy-3/