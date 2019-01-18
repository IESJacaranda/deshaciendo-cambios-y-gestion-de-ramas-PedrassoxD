1. Tienes que modificar la escena 5 de Hamlet en el fichero scene-5.txt. En dicha escena Hamlet encuentra al fantasma de su padre. Añade este texto al fichero:
> Ghost: 
> My hour is almost come,
> When I to sulphurous and tormenting flames
> Must render up myself.
**"nano secene-5.txt" y modificamos**
2. Añade scene-5.txt al área de preparación.
**git add scene-5.txt**
3. Haz un commit con los cambios con un buen mensaje de commit.
**git commit -m "Mensaje añadido"**
4. Modifica las palabras del fantasma. Aquí tienes una sugerencia divertida:
> Ghost: 
> My hour is almost come,
> When I to sulphurous and tormenting balloons
> Must render up myself.
**"git nano scene-5.txt" y modificamos**
5. Devuelve el fichero al estado del último commit.
**git reset --mixed rutadelultimocommit**
6. Cambia el nombre de LARRY por LAERTES en los ficheros scene-3.txt y scene-7.txt.
**"nano scene-3.txt" y modificamos el nombre, lo mismo pero para scene-7.txt**
7. Añade los ficheros al área de preparación usando un único comando git.
**"nano scene-3.txt" y modificamos, lo mismo con scene-7.txt**
8. Vamos a cometer un error a propósito. Borra cualquier línea del fichero scene-2.txt.
**"nano scene-2.txt" y borramos**
9. Añade scene-2.txt al área de preparación.
**git add scene-2.txt**
10. Comprueba el estado del repositorio.
**git status**
11. Devuelve scene-2.txt al directorio de trabajo.
**git rm --cached scene-2.txt**
12. Haz un commit para guardar los cambios realizados en el nombre de Larry por Laertes.
**Tenemos que añadir los ficheros al area de preparacion con "git add ficheroquesea"**
**git commit -m "Añado LAERTES"**
13. Busca el primer commit que has hecho y vuelve a dicho commit. Indica como has buscado el commit anterior y como has vuelto a él.

14. Crea una nueva rama llamada **reinventando_hamlet**
**git branch reinventando_hamlet**
15. Cámbiate a dicha rama
**git checkout reinventando_hamlet**
16. Mejora la escena 2 como creas conveniente.
**"nano scene-2.txt" y modificamos"**
17. Haz un commit con los cambios con un mensaje adecuado.
**git commit -m "Mejora de hamlet"**
18. Vuelve a la rama master.
**git checkout master**
19. Elimina la rama **reinventando_halet**
**git branch -d reinventando_hamlet**
20. Crea una nueva rama, modifica algo en la rama master, haz commit y llévate los cambios a la rama que has creado.
**"git branch nuevarama", modificamos algo en la rama master, hacemos "git commit -m "comentario"", nos cambiamos a la nueva rama y hacemos "git merge master" para traernos los cambios**
21. Provoca un conflicto entre la rama master y la rama que has creado (indica lo que has hecho). Une la rama a la rama master resolviendo el conflicto.
**He creado un nuevo archivo llamado conflicto en la rama master con una linea, lo añado a el area de preparacion y hago commit, despues me cambio a la nuevarama y le hago lo mismo, me cambio a la rama master y al unirlas con "git merge nuevarama" me daría el error del conflicto**.
