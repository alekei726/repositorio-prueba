commit inicial
touch README.md
git add README.md
git status
git commit -m "cracion de archivo readme"
git push
touch privado.txt
mkdir privada
touch .gitignore
echo "Hola mundo" > 1.txt
git add 1.txt
git commit -m "Añadir archivo 1.txt"
git branch v0.2
git checkout v0.2
git add 1.txt
echo "Hola mundo 2" > 2.txt
git add 2.txt
git commit -m "Añadir 1.txt y 2.txt en la rama v0.2"
git push origin v0.2
git switch main
git merge v0.2
echo "Hola" > 1.txt
git add 1.txt
git commit -m "Poner Hola en el fichero 1.txt"
git branch -d v0.2
git push origin --delete v0.2
