Create venv
E:\_usb\py_palabras>..\Winpython-64bit-3.10.90\python-3.10.9.amd64\python.exe -m venv .venv

Activar el ambnient:
E:\_usb\py_palabras>.venv\Scripts\activate


…or create a new repository on the command line
echo "# py_palabras" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:mcaycedo/py_palabras.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin git@github.com:mcaycedo/py_palabras.git
git branch -M main
git push -u origin master