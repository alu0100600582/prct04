Práctica 4
Francisco Mendoza González
Saray Díaz Hernández



Conflictos encontrados:

Console[

alu4271@cc418:~/datos/homes.rala/LPP/practica4$ git merge Fran
error: 'merge' is not possible because you have unmerged files.
hint: Fix them up in the work tree,
hint: and then use 'git add/rm <file>' as
hint: appropriate to mark resolution and make a commit,
hint: or use 'git commit -a'.
fatal: Exiting because of an unresolved conflict.
alu4271@cc418:~/datos/homes.rala/LPP/practica4$ vi matrix.rb 
alu4271@cc418:~/datos/homes.rala/LPP/practica4$ clear

alu4271@cc418:~/datos/homes.rala/LPP/practica4$ git push -u origin master
To git@github.com:alu0100600582/prct04.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'git@github.com:alu0100600582/prct04.git'
To prevent you from losing history, non-fast-forward updates were rejected
Merge the remote changes (e.g. 'git pull') before pushing again.  See the
'Note about fast-forwards' section of 'git push --help' for details.
alu4271@cc418:~/datos/homes.rala/LPP/practica4$ git merge Fran
error: 'merge' is not possible because you have unmerged files.
hint: Fix them up in the work tree,
hint: and then use 'git add/rm <file>' as
hint: appropriate to mark resolution and make a commit,
hint: or use 'git commit -a'.
fatal: Exiting because of an unresolved conflict.

]



Hemos tenido diversos conflictos a la hora de mezclar las ramas de trabajo, estos han sido resueltos mediante el uso del comando
'pull' a la hora de mezclarlas. De esta manera hemos podido mezclar las ramas de trabajo con la rama master y lograr finalmente 
propósito de la práctica.
