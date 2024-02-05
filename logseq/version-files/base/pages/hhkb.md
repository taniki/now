type:: keyboard

- ressources
	- https://happyhackingkb.com/download/
-
- firmware actuel : `A0.46`
-
- configuration supplémentaire pour gnome
	- layout : US intl with dead alt gr
	- gnome-tweaks
		-
-
- différence entre linux et mac os
	- accents ne sont plus mappés par pareil.
	- `ctr+c` devient `command+c` de même avec d'autres raccourcis système mais pas tout le temps non plus
-
- layout original
	- https://hhkb.io/layout/
	- http://hhkb.io/img/misc/hhkbansi-layout1.png{:height 258, :width 730}
-
- pourquoi j'ai choisi un ((659c4fc2-cf27-4cfb-ab29-61fc3f604777))
	- staggered
		- envie de réduire la différence avec le clavier du macbook du travail
			- avant cela j'utilisais des typematrix, olkb et des variantes (plaid)
			- le principe est d'aligner au maximum MacOS sur linux et non l'inverse
			- la [config colemak-dh officielle](https://github.com/ColemakMods/mod-dh) a déjà les accents comme sous linux
			- cette [config](https://github.com/xv0x7c0/osx-us-altgr-intl) me permet d'avoir le layout US AltGr International sous MacOS
			- pour l'instant je laisse `ctrl` et `command` à leurs places sous MacOS
	- blank keycap
		- j'utilise colemak-dh-matrix et c'était le plus simple plutôt que de chercher des keycaps sans différence entre les rangs et compatible avec la souche TOPRE
	- fonctionne out of the box
		- pas le temps de faire de la soudure
			- sur le plaid, il y a une ou deux soudures défaillantes et je n'ai jamais eu le courage de ressouder
		- pas le temps de faire une config QMK même s'il y a des choses qui vont me manquer comme avoir `space` et `shift` sur la même touche
		- j'ai passé maximum 10 minutes maximum dans le configurateur hhkb
	- monobloc vs split
		- je trouve que cela fait moins de bazar sur mon bureau et aussi cela m'éloigne du clavier du portable
		- je trouve cela plus pratique quand je dois bosser à l'extérieur aussi
	- sans fil
		- moins de bazar
		- moins de manip quand je passe d'un ordinateur à l'autre
	- fonctionne avec deux piles AA
		- j'aime bien ce petit côté facile à trouver alors que sourcer de quoi faire un custom keyboard sans fil m'a toujours paru être tout un périple
	- topre/type-s
		- il est thocky de façon satisfaisante sans effort