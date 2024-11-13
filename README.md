# -TP10.
King of POP@tiarayro MINGW64 / (main)
$ mkdir git-ejercicio
King of POP@tiarayro MINGW64 / (main)
$ cd git-ejercicio
King of POP@tiarayro MINGW64 /git-ejercicio (main)
$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint: git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint: git branch -m <name>
Initialized empty Git repository in
C:/Users/YourUserName/Downloads/PortableGit-2.47.0.2-64-bit.7z/git-ejercicio/.git/
King of POP@tiarayro MINGW64 /git-ejercicio (master)
$ nano hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (master)
$ git add hello.py
warning: in the working copy of 'hello.py', LF will be replaced by CRLF the next time Git
touches it
King of POP@tiarayro MINGW64 /git-ejercicio (master)
$ git commit -m "Primer commit: Archivo hello.py"
[master (root-commit) 13d5dce] Primer commit: Archivo hello.py
1 file changed, 1 insertion(+)
create mode 100644 hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (master)
$ git branch rama1
King of POP@tiarayro MINGW64 /git-ejercicio (master)
$ git checkout rama1
Switched to branch 'rama1'
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ cd git-ejercicio
bash: cd: git-ejercicio: No such file or directory
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ ls
hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ nano hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ git add hello.py
warning: in the working copy of 'hello.py', LF will be replaced by CRLF the next time Git
touches it
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ git commit -m "Modificación en Rama2"
[rama1 7a9391b] Modificación en Rama2
1 file changed, 1 insertion(+), 1 deletion(-)
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ git checkout rama1
Already on 'rama1'
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ git merge rama2
merge: rama2 - not something we can merge
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ cd git-ejercicio
bash: cd: git-ejercicio: No such file or directory
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ ls
hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ nano hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ git add hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ git add hello.py
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ git commit -m "Conflicto resuelto: Manteniendo cambios de rama1"
On branch rama1
nothing to commit, working tree clean
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ cd git-ejercicio
bash: cd: git-ejercicio: No such file or directory
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ mkdir proyecto-ejercicio
King of POP@tiarayro MINGW64 /git-ejercicio (rama1)
$ cd proyecto-ejercicio
King of POP@tiarayro MINGW64 /git-ejercicio/proyecto-ejercicio (rama1)
$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint: git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint: git branch -m <name>
Initialized empty Git repository in
C:/Users/YourUserName/Downloads/PortableGit-2.47.0.2-64-bit.7z/git-ejercicio/proyecto-ejercicio/.git/
King of POP@tiarayro MINGW64 /git-ejercicio/proyecto-ejercicio (master)
$ nano contador.py
King of POP@tiarayro MINGW64 /git-ejercicio/proyecto-ejercicio (master)
$ git add contador.py
warning: in the working copy of 'contador.py', LF will be replaced by CRLF the next time Git
touches it
King of POP@tiarayro MINGW64 /git-ejercicio/proyecto-ejercicio (master)
$ git commit -m "Conflicto resuelto: Contador inicia en 1 e incrementa por n"
[master (root-commit) 4fc752d] Conflicto resuelto: Contador inicia en 1 e incrementa por n
1 file changed, 6 insertions(+)
create mode 100644 contador.py
King of POP@tiarayro MINGW64 /git-ejercicio/proyecto-ejercicio (master)
