Creando un repositorio para Robert
Primer paso hacerte una cuenta de git hub
Segundo paso: instalar git
Tercer paso: crear un repositorio con tu cuenta en la pgina web de git hub
Cuarto paso: Abrir el visual code, colocandolo en la carpeta donde quieres trabajar con los archivos 
Quinto paso: Escribir en la terminal de PowerShell el comando "git init" esto crea una carpeta en la direccion en la que estas
!!! cuidado si te equivocas de carpeta, puedes borrar archivos importantes sin querer!!!, para volver al paso anterior (git init) borrar la carpeta 'oculta' de git,
Sexto paso: Comando git remote add origin 'escribe la direccion de tu repositorio, la puedes encontrar en tu cuenta de git hub', con esto indicamos que el git iniciado en el pc esta vinculado al repositorio que creaste en el paso Tercero.
Septimo paso: Comando git add . (añade todos los archivos de tu direccion a la carpeta iniciada de git) o git 'nombre del archivo ejemplo: foto.png' (añade solo el archivo indicado)
Octavo paso: Comando git commit -m "'agregas un comentario del cambio que acabas de hacer'" (con esto se clasifican los cambios hechos hasta hora y se preparan bajo la etiqueta, del comentario, del comando, de este Octavo paso)
Noveno paso: Comando git push (carga el git commit preparado, en el repositorio online de tu cuenta de git hub, vinculado en el Sexto paso a tu git en la direccion donde lo iniciaste, en el Quinto paso)
Decimo paso: Si es la primera vez que pusheas un commit en el repositorio, te pedira que lo confirmes con un comando, aparece en la terminal de PowerShell despues de pushear.

Como usar ramas secundarias.
Primer paso: comando git branch rama_nueva (creas la rama nueva)
Segundo paso: comando git branch (lista de ramas)
Tercer paso: comando git checkout rama_nueva (nos colocamos en la nueva_rama)
Cuarto paso: hacemos los cambios que queramos y otra vez git add . con git commit -m "comentario" y git push (si es la primera vez que pusheas en la nueva rama te pedira lo mismo que en el Decimo paso de 'creando un repositorio'
Quinto paso: comando git checkout master (nos posicionamos en la rama master
Sexto paso: comando git merge nueva_rama (fusiona la ramas)
Septimo paso: comando git branch -d nueva_rama (si quieres borrar la rama hijo, pero solo si fusionaste la hijo con la master) git branch -D nueva_rama (lo mismo pero lo borrar sin importar si la fusionaste o no)
