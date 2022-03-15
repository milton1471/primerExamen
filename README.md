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

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (main)
$ git checkout desarrollo
Switched to branch 'desarrollo'
M       OneDrive/Desktop/DH/prueba.html

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git commit -m "nueva rama"
warning: could not open directory 'AppData/Local/Archivos temporales de Internet
/': Permission denied
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Documents/Mi música/': Permission denied
warning: could not open directory 'Documents/Mis imágenes/': Permission denied
warning: could not open directory 'Documents/Mis vídeos/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch desarrollo
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../DH/prueba.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../../.bash_history
        ../../../.gitconfig
        ../../../.lesshst
        ../../../.vscode/
        ../../../3D Objects/
        ../../../ASD/
        ../../../AppData/
        ../../../Contacts/
        ../../../Downloads/
        ../../../Favorites/
        ../../../Links/
        ../../../Music/
        ../../../NTUSER.DAT
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000001.regtrans-ms
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000002.regtrans-ms
        ../../.849C9593-D756-4E56-8D6E-42412F2A707B
        ../Armando pc/
        ../CSS/
        ../Comandos github.png
        ../Counter-Strike.url
        ../DH/Front End/
        ../DH/PROYECTO INTEGRADOR/
        ../Discord.lnk
        ../Documento.rtf
        ../Examen front.png
        ../GIT.txt
        ../GIT/
        ../GOMAS AUTO.txt
        ../Gamers Club Anti-Cheat.lnk
        ../Injected Anti-cheat.lnk
        ../Links actividades DH/
        ../Manifiesto del equipo.pdf
        ../Nueva carpeta/
        ../Prueba asd/
        ../Prueban/
        ../Repositorio/
        "../Rocket League\302\256.url"
        ../Trabajo clase 12.rtf
        ../Visual Studio Code.lnk
        ../Zoom.lnk
        ../clips torneo.txt
        ../desktop.ini
        ../mi footer.txt
        ../pajaro.jpg
        ./
        ../pws.txt
        ../repositorio1/
        ../rontend-ctd-clase7-main.zip
        ../tarea/
        ../../Documents/
        ../../Pictures/
        ../../../Repositorio/
        ../../../Saved Games/
        ../../../Searches/
        ../../../Videos/
        ../../../ntuser.dat.LOG1
        ../../../ntuser.dat.LOG2
        ../../../ntuser.ini

no changes added to commit (use "git add" and/or "git commit -a")

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git checkout desarrollo
Already on 'desarrollo'
M       OneDrive/Desktop/DH/prueba.html

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ touch Readme.md

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git commit -m "Examen"
warning: could not open directory 'AppData/Local/Archivos temporales de Internet
/': Permission denied
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Documents/Mi música/': Permission denied
warning: could not open directory 'Documents/Mis imágenes/': Permission denied
warning: could not open directory 'Documents/Mis vídeos/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch desarrollo
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../DH/prueba.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../../.bash_history
        ../../../.gitconfig
        ../../../.lesshst
        ../../../.vscode/
        ../../../3D Objects/
        ../../../ASD/
        ../../../AppData/
        ../../../Contacts/
        ../../../Downloads/
        ../../../Favorites/
        ../../../Links/
        ../../../Music/
        ../../../NTUSER.DAT
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000001.regtrans-ms
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000002.regtrans-ms
        ../../.849C9593-D756-4E56-8D6E-42412F2A707B
        ../Armando pc/
        ../CSS/
        ../Comandos github.png
        ../Counter-Strike.url
        ../DH/Front End/
        ../DH/PROYECTO INTEGRADOR/
        ../Discord.lnk
        ../Documento.rtf
        ../Examen front.png
        ../GIT.txt
        ../GIT/
        ../GOMAS AUTO.txt
        ../Gamers Club Anti-Cheat.lnk
        ../Injected Anti-cheat.lnk
        ../Links actividades DH/
        ../Manifiesto del equipo.pdf
        ../Nueva carpeta/
        ../Prueba asd/
        ../Prueban/
        ../Repositorio/
        "../Rocket League\302\256.url"
        ../Trabajo clase 12.rtf
        ../Visual Studio Code.lnk
        ../Zoom.lnk
        ../clips torneo.txt
        ../desktop.ini
        ../mi footer.txt
        ../pajaro.jpg
        ./
        ../pws.txt
        ../repositorio1/
        ../rontend-ctd-clase7-main.zip
        ../tarea/
        ../../Documents/
        ../../Pictures/
        ../../../Repositorio/
        ../../../Saved Games/
        ../../../Searches/
        ../../../Videos/
        ../../../ntuser.dat.LOG1
        ../../../ntuser.dat.LOG2
        ../../../ntuser.ini

no changes added to commit (use "git add" and/or "git commit -a")

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git add readme.md

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git commit -m "Examen"
warning: could not open directory 'AppData/Local/Archivos temporales de Internet
/': Permission denied
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Documents/Mi música/': Permission denied
warning: could not open directory 'Documents/Mis imágenes/': Permission denied
warning: could not open directory 'Documents/Mis vídeos/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch desarrollo
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../DH/prueba.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../../.bash_history
        ../../../.gitconfig
        ../../../.lesshst
        ../../../.vscode/
        ../../../3D Objects/
        ../../../ASD/
        ../../../AppData/
        ../../../Contacts/
        ../../../Downloads/
        ../../../Favorites/
        ../../../Links/
        ../../../Music/
        ../../../NTUSER.DAT
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000001.regtrans-ms
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000002.regtrans-ms
        ../../.849C9593-D756-4E56-8D6E-42412F2A707B
        ../Armando pc/
        ../CSS/
        ../Comandos github.png
        ../Counter-Strike.url
        ../DH/Front End/
        ../DH/PROYECTO INTEGRADOR/
        ../Discord.lnk
        ../Documento.rtf
        ../Examen front.png
        ../GIT.txt
        ../GIT/
        ../GOMAS AUTO.txt
        ../Gamers Club Anti-Cheat.lnk
        ../Injected Anti-cheat.lnk
        ../Links actividades DH/
        ../Manifiesto del equipo.pdf
        ../Nueva carpeta/
        ../Prueba asd/
        ../Prueban/
        ../Repositorio/
        "../Rocket League\302\256.url"
        ../Trabajo clase 12.rtf
        ../Visual Studio Code.lnk
        ../Zoom.lnk
        ../clips torneo.txt
        ../desktop.ini
        ../mi footer.txt
        ../pajaro.jpg
        ./
        ../pws.txt
        ../repositorio1/
        ../rontend-ctd-clase7-main.zip
        ../tarea/
        ../../Documents/
        ../../Pictures/
        ../../../Repositorio/
        ../../../Saved Games/
        ../../../Searches/
        ../../../Videos/
        ../../../ntuser.dat.LOG1
        ../../../ntuser.dat.LOG2
        ../../../ntuser.ini

no changes added to commit (use "git add" and/or "git commit -a")

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git status
warning: could not open directory 'AppData/Local/Archivos temporales de Internet
/': Permission denied
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Documents/Mi música/': Permission denied
warning: could not open directory 'Documents/Mis imágenes/': Permission denied
warning: could not open directory 'Documents/Mis vídeos/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch desarrollo
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../DH/prueba.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../../.bash_history
        ../../../.gitconfig
        ../../../.lesshst
        ../../../.vscode/
        ../../../3D Objects/
        ../../../ASD/
        ../../../AppData/
        ../../../Contacts/
        ../../../Downloads/
        ../../../Favorites/
        ../../../Links/
        ../../../Music/
        ../../../NTUSER.DAT
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000001.regtrans-ms
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000002.regtrans-ms
        ../../.849C9593-D756-4E56-8D6E-42412F2A707B
        ../Armando pc/
        ../CSS/
        ../Comandos github.png
        ../Counter-Strike.url
        ../DH/Front End/
        ../DH/PROYECTO INTEGRADOR/
        ../Discord.lnk
        ../Documento.rtf
        ../Examen front.png
        ../GIT.txt
        ../GIT/
        ../GOMAS AUTO.txt
        ../Gamers Club Anti-Cheat.lnk
        ../Injected Anti-cheat.lnk
        ../Links actividades DH/
        ../Manifiesto del equipo.pdf
        ../Nueva carpeta/
        ../Prueba asd/
        ../Prueban/
        ../Repositorio/
        "../Rocket League\302\256.url"
        ../Trabajo clase 12.rtf
        ../Visual Studio Code.lnk
        ../Zoom.lnk
        ../clips torneo.txt
        ../desktop.ini
        ../mi footer.txt
        ../pajaro.jpg
        ./
        ../pws.txt
        ../repositorio1/
        ../rontend-ctd-clase7-main.zip
        ../tarea/
        ../../Documents/
        ../../Pictures/
        ../../../Repositorio/
        ../../../Saved Games/
        ../../../Searches/
        ../../../Videos/
        ../../../ntuser.dat.LOG1
        ../../../ntuser.dat.LOG2
        ../../../ntuser.ini

no changes added to commit (use "git add" and/or "git commit -a")

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git push origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/milton1471/primerExamen.g
it'

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ git commit -m "mensaje"
warning: could not open directory 'AppData/Local/Archivos temporales de Internet
/': Permission denied
warning: could not open directory 'Configuración local/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Datos de programa/': Permission denied
warning: could not open directory 'Documents/Mi música/': Permission denied
warning: could not open directory 'Documents/Mis imágenes/': Permission denied
warning: could not open directory 'Documents/Mis vídeos/': Permission denied
warning: could not open directory 'Entorno de red/': Permission denied
warning: could not open directory 'Impresoras/': Permission denied
warning: could not open directory 'Menú Inicio/': Permission denied
warning: could not open directory 'Mis documentos/': Permission denied
warning: could not open directory 'Plantillas/': Permission denied
warning: could not open directory 'Reciente/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
On branch desarrollo
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../DH/prueba.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../../../.bash_history
        ../../../.gitconfig
        ../../../.lesshst
        ../../../.vscode/
        ../../../3D Objects/
        ../../../ASD/
        ../../../AppData/
        ../../../Contacts/
        ../../../Downloads/
        ../../../Favorites/
        ../../../Links/
        ../../../Music/
        ../../../NTUSER.DAT
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000001.regtrans-ms
        ../../../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer000
00000000000000002.regtrans-ms
        ../../.849C9593-D756-4E56-8D6E-42412F2A707B
        ../Armando pc/
        ../CSS/
        ../Comandos github.png
        ../Counter-Strike.url
        ../DH/Front End/
        ../DH/PROYECTO INTEGRADOR/
        ../Discord.lnk
        ../Documento.rtf
        ../Examen front.png
        ../GIT.txt
        ../GIT/
        ../GOMAS AUTO.txt
        ../Gamers Club Anti-Cheat.lnk
        ../Injected Anti-cheat.lnk
        ../Links actividades DH/
        ../Manifiesto del equipo.pdf
        ../Nueva carpeta/
        ../Prueba asd/
        ../Prueban/
        ../Repositorio/
        "../Rocket League\302\256.url"
        ../Trabajo clase 12.rtf
        ../Visual Studio Code.lnk
        ../Zoom.lnk
        ../clips torneo.txt
        ../desktop.ini
        ../mi footer.txt
        ../pajaro.jpg
        ./
        ../pws.txt
        ../repositorio1/
        ../rontend-ctd-clase7-main.zip
        ../tarea/
        ../../Documents/
        ../../Pictures/
        ../../../Repositorio/
        ../../../Saved Games/
        ../../../Searches/
        ../../../Videos/
        ../../../ntuser.dat.LOG1
        ../../../ntuser.dat.LOG2
        ../../../ntuser.ini

no changes added to commit (use "git add" and/or "git commit -a")

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$ ^C

milto@DESKTOP-03HF7M9 MINGW64 ~/onedrive/desktop/primerExamen (desarrollo)
$
