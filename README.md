# SC635A_TEST

programma per la validazione delle schede

Contiene sottoprogetti, usare: git clone --recursive 

Per aggiornare bsp:
	1) cd bsp
	2) git fetch
	3) git merge origin/master
	4) cd ..
	5) git commit -am 'aggiornato bsp'
	6) git push
oppure:
	1) git submodule update --remote bsp
	2) git commit -am 'aggiornato bsp'
	3) git push
