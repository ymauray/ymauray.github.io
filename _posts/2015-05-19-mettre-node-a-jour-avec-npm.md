---
layout: post
title: Mettre node.js à jour via npm
excerpt: "Utiliser node.js pour mettre node.js à jour"
tags: [node, npm]
comments: true
---
Pour mettre à jour node.js le plus simplement du monde, il suffit d'utiliser les commandes suivantes (sous linux) :
{% highlight bash linenos %}
$ sudo npm cache clean -f
$ sudo npm install -g n
$ sudo n stable
{% endhighlight %}

Le package "n" est un utilitaire, la dernière commande permet de mettre node (et npm) à jour avec la dernière version stable.

Cette information à été trouvée ici : http://davidwalsh.name/upgrade-nodejs
