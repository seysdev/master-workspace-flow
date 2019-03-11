#Git y sus comandos
Git es un software open source para el manejo de control de versiones

###La anatomia de un comando es la siguiente 
Todos los comandos se componen de:

* El prefijo __git__.
* El verbo.
* Atributos del verbo.
* Argumentos sobre los que actúa el verbo. 

__Ejemplos:__
* git init
* git add nombre_archivo
* git commit -m "first commit"

###Comandos
* __git help:__ Muestra ayuda de comandos
```
git help
```

* __git init:__ Crea un repositorio de manera local
```
git init
```

* __git clone url:__ Clonar repositorio.
```
git clone 
```

* __git add + path/file:__ Añadir archivos para un commit
```
git add .
```

* __git commit:__ Enviar un commit
```
git commit -m "mensaje corto"
```

* __git push [rama remota][rama]:__ Enviar un commit
```
git push origin master
```

* __git pull [rama remota][rama]:__ Descarga los cambios y los mezcla
```
git pull origin master
```

* __git branch [-a][-r]:__ Lista ramas
```
git branch 
```

* __git log:__ Lista historial de commits
```
git log 
```

* __git checkout [rama]:__ Cambiar de rama
```
git checkout "nombre-rama"
```

* __git checkout -- "nombre-archivo":__ Quitar cambios del stage
```
git checkout -- "nombre-archivo"
```

* __git checkout -b "nombre rama":__ Crea rama local
```
git checkout -b "nombre rama"
```





