# GitNuestro
**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?** 

*git reset --hard HEAD~1 . Utilice este porque me permitia perder los 
cambios en el 
working copy*

**-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?** 

*git reflog --> Miramos el commit que queremos ir. Buscamos el 
identificador
git reset --hard identificador . 
Porque puedo ver el paso que habia antes de deshacer el commit*

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

*No causo ningún conflicto. Porque  el archivo git-nuestro.md que a 
absorbido styled
es una modificacion del archivo padre en master.*

**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

*Si causo conflicto. Porque el archivo que tiene htmlify esta en una 
rama diferente al 
styled. Git compara los archivos y ve que son distintos.*

**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

*No causo ningún conflicto. Por que la rama styled ya contiene lo de la 
rama master.*

**- ¿Qué comando o comandos utilizaste en el paso 25?**

*git log --graph --decorate --pretty=oneline*

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

*Si, por que la rama title contiene todo de rama padre en este caso 
seria master*

**- ¿Qué comando o comandos utilizaste en el paso 27?**

*git reset HEAD~1 para deshacer el merge sin perder cambios working 
copy*

**- ¿Qué comando o comandos utilizaste en el paso 28?**

*git checkout -- git-nuestro.md*

**- ¿Qué comando o comandos utilizaste en el paso 29?**

*git branch -D title desde master*

**- ¿Qué comando o comandos utilizaste en el paso 30?**

*git reset --hard <codigo identificador del paso anterior mirando 
reflog>*

**- ¿Qué comando o comandos usaste en el paso 32?**

*Hacemos git log y luego miramos el commit inicial. Escribimos git 
checkout 
<identificador del commit>. Entramos en detached HEAD. Nuestro HEAD 
apunta al primer 
commit.*

**- ¿Qué comando o comandos usaste en el punto 33?**

*git checkout <idenficamos el commit donde pusimos el titulo>* 

