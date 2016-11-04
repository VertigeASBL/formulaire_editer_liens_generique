# Formulaire d'édition de liens générique #

Le formulaire `#FORMULAIRE_EDITER_LIENS` de SPIP n'est pas très flexible, il ne permet p.ex. que de gérer les liens dans un seul sens.
Je m'explique : si j'ai une liaison « many-to-many » entre des « Personnes » et des « Sociétés » gérée dans une table `spip_personnes_liens`, je ne peux me servir du `#FORMULAIRE_EDITER_LIENS` que pour gérer les personnes associées à une société donnée, mais pas l'inverse.

L'objectif de ce plugin est de palier à ce manque.
