# SC635A_TEST

programma per la validazione delle schede

Contiene sottoprogetti, usare: git clone --recursive 

Per aggiornare bsp:
1. cd bsp
1. git fetch
1. git merge origin/master
1. cd ..
1. git commit -am 'aggiornato bsp'
1. git push

oppure:
1. git submodule update --remote bsp
1. git commit -am 'aggiornato bsp'
1. git push
