# Si empezamos desde 0:

    *git init
    *git add .
    *git commit -m 'comentario X'
    *git branch -M main

**Debemos crear un repo en GitHub**

    *git remote add origin https://github.com/Lepori99/Clases_pwi_tn_abril_UTN.git
    *git push -u origin main


Listo, con esto tenemos nuestro repo en github con lo que hayamos subido


**Podemos usar git status para obtener una informacion detallada del estado de nuestro repo**

# Si estoy actualizando:

    *git add .
    *git commit -m 'comentario'
    *git push


# ACLARACIONES:

**Si me equivoque al poner el git remote usamos el comando**

    *git remote set-url origin <URL_CORRECTA>

**Podemos usar git status para obtener una informacion detallada del estado de nuestro repo**

    *git status

**Para ver que origen remoto tengo**

    *git remote -v


# Para clonar un repositorio usar:

    *git clone URL