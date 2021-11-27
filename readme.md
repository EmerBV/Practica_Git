# Preguntas:

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
*Ejecuto el comando git reset --hard HEAD~1*
*De esta manera deshago el último commit y lo que había en el working copy dejándolo todo como estaba anteriormente.*
**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
*Primero ejecuto el comando git reflog para saber el identificador del commit que he deshecho. Una vez identificado dicho commit,*
*ejecuto el comando git reset --hard más el identificador del commit que quiero rehacer, que en mi caso era el "cdc6763" y finalmente*
*ejecuto el comando git log para comprobar que se ha rehecho satisfactoriamente. También he ejecutado el comando cat git-nuestro.md*
*para comprobar que todo estaba como antes de deshacer el último commit.*
**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
*No, ya que al absorber master éste ya tenía los mismos commits que había en el master.*
**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
*Sí, porque he modificado el mismo archivo en las mismas líneas y en dos ramas diferentes.*
**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
*No, lo único que ha ejecutado ha sido un merge Fast-forward absorviendo los commits que tiene la rama styled.*
**¿Qué comando o comandos utilizaste en el paso 25?**
*Primero ejecuto el comando git log para ver el log de los commits de la rama master. Y finalmente ejecuto*
*el comando git log --graph*
**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
*Sí, ya que absorbería igualmente el trabajo que hay hecho en la rama de title. Al igual que sin fast forward*
*absorvería los commits que hay en title sólo que éste generaría un commit nuevo con dos padres.*
**¿Qué comando o comandos utilizaste en el paso 27?**
*Ejecuto el comando git reset HEAD~1*
**¿Qué comando o comandos utilizaste en el paso 28?**
*Ejecuto el comando git checkout -- git-nuestro.md*
**¿Qué comando o comandos utilizaste en el paso 29?**
*Primero ejecuto el comando git checkout master ya que git no me dejaría eliminar la rama title si estuviera en ella.*
*Ejecuto el comando git branch -D title*
**¿Qué comando o comandos utilizaste en el paso 30?**
*Primero ejecuto el comando git reflog para ver el identificador del commit donde hice el merge y finalmente ejecuto*
*el comando git reset --hard mas el identificador correspondiente al merge que deshice.*
**¿Qué comando o comandos usaste en el paso 32?**
*Primero ejecuto el comando git reflog para ver el identificador del commit inicial y finalmente ejecuto el comando*
*git checkout más el identificador del commit inicial.*
**¿Qué comando o comandos usaste en el punto 33?**
*Ejecuto el comando git checkout master*
