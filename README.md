# Curso Git and GitHub

Holaaaaaaaaaaaaaaaaaaaaaaaa.

Pruebita :3 

Todo funciona Okey <3

Pasos:
git --version
git config --global user.name "Marycielo Martel"
git config --global user.email olenkamartel.j7@gmail.com
git config --global user.ui true (coloreará automáticamente la mayor parte de los resultados que muestre)
git config --global init.defaultBranch main
git config --list

# asignando visual studio code como editor de configuración de git

git config --global core.editor "code --wait"
git config --global -e
git config --global core.autocrlf true (Si estás programando en Windows, para estandarizar los saltos de linea de windows)
git config -h (opciones de configuraciones en la terminal)
git help config ( opciones configuraciones en el navegador)


# Iniciar un directorio

mkdir carpeta
cd carpeta
touch README.md
touch .gitignore
git init
code .

# Git and GitHub

git add . (todos los cambios)
git commit -m "mensaje descriptivo" (agregar commit automatico)

En GitHub agregar un nuevo repositorio y en los pasos que te salen copiar:
git remote add origin https://github.com/usuario/repositorio.git

git push -u origin main

Para los siguientes cambios o actualizaciones solo:
git add.
git commit -m "name"
git push

