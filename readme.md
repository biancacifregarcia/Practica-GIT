# Práctica GIT

### Cifre García, Bianca

# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Porqué?**

`git reset --hard HEAD~1` 

Se utiliza este comando para deshacer el último commit y lo que había en el Working copy.

--


**2. ¿Qué comando utilizaste en el paso 12? ¿Porqué?**

`git reflog ` `git reset --hard 5ac3f79  ` 

Anterior al comando anterior utilicé
`git reflog ` para así averigur el identificador del commit que había deshecho.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Porqué?**
Sí, debido a que ya estaba actualizada la rama styled con la rama master. Al intentar que styled absorba a master, no lo hace ya que poseen la misma información.


--
**4. El merge del paso 19, ¿Causó algún conflicto? ¿Porqué?**

Sí, debido a que se ha modicado el archivo en dos ramas distintas, y no se pueden absorver.

--
**5. El merge del paso 21, ¿Causó algún conflicto? ¿Porqué?**

No ha causado ningun conflicto.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph` 

Se utiliza este comando para que aparezca el diagrama de las ramas en la terminal.

--
**7. El merge del paso 26,¿Podría ser fast forward?¿Porqué?**

Sí, por que al retroceder te encontrarias con la rama anterior.

--
**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 


--
**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reflog` 
`git reset 7fb1eeb` 
`git reset --hard HEAD~1` 




--
**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -d title` 
al confirmar que lo quieres eleminar debes teclear el comando:
`git branch -D title` 


--
**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog ` 
`git reset --hard 7fb1eeb`





--
**12. ¿Qué comando o comandos utilizaste en el paso 32?**

`git reflog ` 
`git checkout e81d8a5 ` 



--
**13. ¿Qué comando o comandos utilizaste en el paso 33?**

`git reflog ` 
`git checkout 7fb1eeb ` 



--



