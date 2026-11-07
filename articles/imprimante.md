---
title: "HELPDESK - Expert Solutions TI - IMPRIMANTE"
source_url: https://sites.google.com/view/it5kb/imprimante
migrated_on: 2026-11-07
status: imported-needs-review
---

# IMPRIMANTE

L'imprimante n'imprime pas:

1. Essayer d'imprimer d'un autre poste

2. Valider les message d'erreur sur l'imprimante

3. Redemarrer l'imprimante

L'imprimante n'est pas installer

Ouvrir un billet de support dans le CHAT sur le HomePage

SCAN to EMAIL

📌 Description du problème

La fonction Scan vers courriel de l’imprimante Canon ne fonctionne pas lorsque les documents sont envoyés vers des adresses [gymfitforme.com](http://gymfitforme.com). Les courriels semblent être envoyés par l’imprimante, mais ils sont bloqués avant d’arriver à destination.

❗ Cause principale

Le domaine @gymfitforme.com applique des règles de sécurité renforcées pour la réception des courriels (SPF).

Le système de courriel exige que l’expéditeur soit autorisé officiellement à envoyer des messages pour le domaine.

L’imprimante Canon envoie les courriels via un serveur SMTP non autorisé.

Le module de courriel de l’imprimante est désuet et ne respecte plus les standards de sécurité actuels.

➡️ Résultat :

Les serveurs de messagerie de @gymfitforme.com bloquent automatiquement ces courriels pour des raisons de sécurité.

🔒 Pourquoi ce blocage est normal

Ce mécanisme de protection existe pour :

Éviter le spam

Prévenir l’usurpation d’identité

Protéger le domaine contre les envois frauduleux

Il s’agit donc d’un blocage volontaire et sécuritaire, et non d’une panne du système de courriel.  

✅ Solutions recommandées  
	Utiliser une clé USB directement sur l'imprimante et SCAN vers USB  
	Envoyer le scan vers une addresse qui n'est pas celle de [gymfitforme.com](http://gymfitforme.com) (attention securité Loi 25)
