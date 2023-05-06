Create venv
E:\_usb\py_palabras>..\Winpython-64bit-3.10.90\python-3.10.9.amd64\python.exe -m venv .venv

Activar el ambnient:
E:\_usb\py_palabras>.venv\Scripts\activate


…or create a new repository on the command line
echo "# py_palabras" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:mcaycedo/py_palabras.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin git@github.com:mcaycedo/py_palabras.git
git branch -M master
git push -u origin master

-------------------------------------------------------------
Para poder usar id_rsa copie la parte publica que esta en 
"C:\Users\Mario Caycedo\.ssh", id_rsa.pub y lo subi al repositorio
Solo acepta un repositorio a la vez
-------------------------------------------------------------
- Inicializar
git init

- Amarrar el repositorio a GIT
git remote add origin git@github.com:mcaycedo/py_palabras.git

- Agregar archivos 
git add file

- Commit:
git commit -m "Cambio version"

- Subirlo al proyecto a GIT
git push -u origin master
pide la passphrase
