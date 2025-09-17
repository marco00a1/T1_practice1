mkdir POO-T1-practice1                       ----> crear carpeta local.
cd POO-T1-practice1                          ----> ingresamos a la carpeta.
git init                                  ----> iniciamos git.
git status                                ----> ver estado actual
git log                                   ----> ver historial de commits
mkdir pregunta1                    ----> creamos las carpetas con los casos.
touch guia_git_t1.md README.md               ----> creamos el archivo .md para la informacion del proyecto.
touch pregunta1/Autor.java      ----> creamos el archivo para el primer caso.
touch pregunta1/Libro.java      ----> creamos el archivo para el primer caso.
touch pregunta1/BibliotecaApp.java      ----> creamos el archivo para el primer caso.
git add .					----> prepara todos los cambios
git commit -m "POO-T1-practice1"			----> crea un commit del cambio
git branch POO-T1-practice1				----> crea una nueva rama llamada POO-casos
git checkout POO-T1-practice1							----> cambiamos a la rama POO-casos
git checkout master								----> denuevo cambiamos a la rama principal
git merge POO-T1-practice1								----> unimos la rama POO-casos dentro de la rama (master)
git remote add origin https://github.com/marco00a1/T1_practice1.git	----> conecta tu repo local con el repo en GitHub
git push -u origin master						----> sube los commits de la rama master a GitHub.
