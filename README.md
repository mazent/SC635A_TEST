# SC635A_TEST

programma per la validazione delle schede

Contiene sottoprogetti, usare: git clone --recursive 

Per aggiornare bsp:
	cd bsp
	git fetch
	git merge origin/master
	cd ..
	git commit -am 'aggiornato bsp'
	git push
oppure:
	git submodule update --remote bsp
	git commit -am 'aggiornato bsp'
	git push
