EJERCICIO PREVIO
git clone https://github.com/asalber/libro-git.git
cd libro-git
git reset --hard cb1e4
git remote remove origin
EJERCICIO 1
Crear el repositorio libro-git en github
git remote add libro-git https://github.com/Mikipower/libro-git
git remote -v
EJERCICIO 2
git push libro-git master
comprobar los cambios en el github
EJERCICIO 3
colaborar en el repositorio remoto de otro compañero (Ayoub Tajeddine)
git clone git clone https://github.com/Ayoub1199/libro-git
git pull
git push
echo Ayoub Tajeddine, Ayoub1199@gmail.com > autores.txt
git add autores.txt
git add libro-git (Se habia quedado sin seguimiento)
git add .
git commit -m "Añadido autor."
git push libro-git master
EJERCICIO 4
git remote -v
git remote add upstream https://github.com/asalber/libro-git.git
git remote -v
git clone https://github.com/Mikipower/libro-git
git checkout -b autoria
echo Asalber Ramirez, Asalber65@gmail.com > autores.txt
git commit -am "Añadido nuevo autor."
git push libro-git autoria
