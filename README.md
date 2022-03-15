# primerExamen
milto@DESKTOP-03HF7M9 MINGW64 ~ (main)
$ cd onedrive

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive (main)
$ cd desktop

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop (main)
$ mkdir primerExamen

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop (main)
$ cd primerExamen

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ mkdir Entrada

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ mkdir Plato-Principal

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ mkdir Postre Pastas Frituras

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ touch Ravioles.txt

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ touch Fideos.txt

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ touch Pollo_Frito.txt

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ touch Helado.txt

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ mv {Fideos.txt Plato-Principal}
mv: cannot stat '{Fideos.txt': No such file or directory

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git mv {Fideos.txt Plato-Principal}
fatal: bad source, source=OneDrive/Desktop/primerExamen/{Fideos.txt, destination
=OneDrive/Desktop/primerExamen/Plato-Principal}

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ cd Plato-Principal

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ rm ../Pastas
rm: cannot remove '../Pastas': Is a directory

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ git rm ../pastas
fatal: pathspec '../pastas' did not match any files

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ git rm ../Pastas
fatal: pathspec '../Pastas' did not match any files

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ git rm ./Pastas
fatal: pathspec './Pastas' did not match any files

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ rmdir Pastas
rmdir: failed to remove 'Pastas': No such file or directory

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ rm Pastas
rm: cannot remove 'Pastas': No such file or directory

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ rm -r Pastas
rm: cannot remove 'Pastas': No such file or directory

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ pwd
/c/Users/milto/onedrive/desktop/primerExamen/Plato-Principal

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen/Plato-Principal (main)
$ cd ..

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ ^[[200~git init
bash: $'\E[200~git': command not found
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/milton1471/primerExamen.git
git push -u origin main
milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git commit -m "first commit"
[main (root-commit) 7e3737f] first commit
 6 files changed, 155 insertions(+)
 create mode 100644 OneDrive/Desktop/DH/img/Logo.jpeg
 create mode 100644 OneDrive/Desktop/DH/img/la bombonera.jpg
 create mode 100644 OneDrive/Desktop/DH/img/lemon-pie 1.jpeg
 create mode 100644 OneDrive/Desktop/DH/index.html
 create mode 100644 OneDrive/Desktop/DH/prueba.html
 create mode 160000 OneDrive/Desktop/mochila_camada7/mochila_camada7

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git branch -M main

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git remote add origin https://github.com/milton1471/primerExamen.git

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git push -u origin main
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 12 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (12/12), 812.18 KiB | 42.75 MiB/s, done.
Total 12 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/milton1471/primerExamen.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git branch <primerExamen>
bash: syntax error near unexpected token `newline'

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git branch desarrollo

