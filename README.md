# Tarea de Materia Controlador de Versiones GIT 

### git init : 
Nos sirve para iniciarlizar el repositorio git dentro de la carpeta.

### git status : 
Ayuda a comporbar en que estado estamos del proyecto, que cambios hemos echo.


On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
no changes added to commit (use "git add" and/or "git commit -a")

-------------------------------------------

### git log :

Muestra todos los commit que se encuentra dentro del repositorio

commit 95b85b59876a79b482a9e326c512364f77148b1a (HEAD -> main, origin/main)
Author: Mario <Mario1995182@gmail.com>
Date:   Fri Oct 27 06:26:22 2023 -0500

    Agregar negrita

commit e848493d67de5cd5e8a2d16645d09d9e777f8f8f
Author: Mario <Mario1995182@gmail.com>
Date:   Thu Oct 26 22:37:41 2023 -0500

    Agregar readme

commit 26219c0ef5583be5a0b190bccf22ce3dd1401796
Author: Mario <Mario1995182@gmail.com>
Date:   Thu Oct 26 22:02:21 2023 -0500

    agregar primer commit
----------------------------------------------------------

### git add + "nombre de archivo" :
Para agregar el archivo a Git 

### git add . :
Agrega todos los cambios realizados dentro del proyecto 

### git Commint :
Agregar el archivo o cambio realizado dentro del repositorio para que se guarde en la linea de tiemop con nombre o descripcion

[main 95b85b5] Agregar negrita
 1 file changed, 4 insertions(+), 1 deletion(-) 
 
-----------------------------------------------------------

### git diff :

Muestra los cambios ejecutados dentro de los archivos

index ef62803..4ebb848 100644
--- a/README.md
+++ b/README.md
@@ -1,6 +1,57 @@
 # Tarea de Materia Controlador de Versiones GIT

-esta es una prueba
+### git init :
+Nos sirve para iniciarlizar el repositorio git dentro de la carpeta.
+
+### git status :
+Ayuda a comporbar en que estado estamos del proyecto, que cambios hemos echo.
+
+
+On branch main
+Your branch is up to date with 'origin/main'.
+
+Changes not staged for commit:
+  (use "git add <file>..." to update what will be committed)
+  (use "git restore <file>..." to discard changes in working directory)
+        modified:   README.md
+no changes added to commit (use "git add" and/or "git commit -a")
+
+-------------------------------------------
+
+### git log :
+
+Muestra todos los commit que se encuentra dentro del repositorio
+
+commit 95b85b59876a79b482a9e326c512364f77148b1a (HEAD -> main, origin/main)
+Author: Mario <Mario1995182@gmail.com>
:

------------------------------------------------------

### git show :
Sirve para ver todas las funciones del commit 

$ git show d6056eca19183b67e70b9eac8019d2bae6cd8045
commit d6056eca19183b67e70b9eac8019d2bae6cd8045 (HEAD -> main, origin/main)
Author: Mario <Mario1995182@gmail.com>
Date:   Fri Oct 27 07:20:14 2023 -0500

     agregar resta

diff --git a/index.js b/index.js
index f7a6d9a..0d32cd4 100644
--- a/index.js
+++ b/index.js
@@ -1,3 +1,7 @@
-function sum (a,b) {
-    return a+b
+function sum(a,b) {
+    return a + b;
 }
+
+function subtract(a, b) {
+    return a - b;
+}
\ No newline at end of file
-------------------------------------------------

### git checkout -b:
Sirve para crear una rama o una tarea independiente a un archivo 

### git checkout:
Nos ayuda a cambiarnos entre ramas 

### git branch: 
Muestra todos los branch que existe 

### git merge: 
Une los branch al main o principal de nuestro proyecto 

### .gitingnore:
ignorara la subida de ciertos archivos al repositorio tales como logs y demas depedencias que no queremos 
que sean compartidas con otros usuarios.

### git rebase:
Sirve para integrar el ultimo Cambio al commit base de nuestro proyecto

### git rebase -i:
Hace cambios interactivos en los commit en la raiz - se puede renombrarlos o unirlos en un solo comit 

### git revert:
Permite revetir un commit guardado

### git stash:
Guarda trabajos en progresos dentro de la pila del git como un tipo "cache" sin necesidad de comitearlos  

### git cherry-pick:
Sirve para aplicar un branch a un comit en especifico 

### git branch -M main: 
Para cambiar a main la raiz  en el caso que esté en master

### git remote -v
Sirve para verificar los remotos que estan configurados

### git push -u origin main:
Para subir los cambios del local al remoto que se realizan en el repositorio

### git push :
Para actualizar el repositoro con el remoto