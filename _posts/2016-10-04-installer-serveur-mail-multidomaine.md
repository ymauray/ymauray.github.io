---
layout: post
title: Installer un serveur de courrier multi-domaine
excerpt: "Installer un serveur de courrier multi-domaine"
tags: [mail, smtp, sals, courrier, imap, starttls]
comments: true
---
Voici un tutoriel qui explique pas par pas comment installer un serveur de courrier multi-domaine. C'est écrit pour Debian 7 (Weezy), mais ça fonctionne aussi pour Ubuntu.

https://www.howtoforge.com/virtual-users-and-domains-with-postfix-courier-mysql-and-squirrelmail-debian-wheezy

Note : si au bout d'un moment il n'est plus possible d'envoyer un message, il se peut qu'il faille relancer saslauthd. Il faut vérifier s'il y a des erreurs de type "auth_pam: pam_authenticate failed: Memory buffer error" dans le fichier /var/log/auth.log
