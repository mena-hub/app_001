#### Web Personal para deployar en PythonAnywhere
*por Jeremías Cáceres*

Primer proyecto del curso Python + Django. 

Lo trabajado acá, en parte, ya fue listado. Se puede agregar:

- Create project
- Create application
- Function-Based Views
- URL Mapping
- Models

**¿Nos hace falta algo?**

- requirements.txt
- [PythonAnywhere](https://www.pythonanywhere.com/)

**NOTA**

1. Los códigos van siendo actualizados sin un orden y nunca al 100%.

2. De ser posible, se mantiene la versión del framework y de las librerías. 

3. Ese no es el caso de Pillow que requiere sí o sí su último lanzamiento.

**NOTA DOS**

Queda pendiente el deploy en PythonAnywhere... hecho y ahora deshecho.

**NOTA TRES**

El repositorio se subió un 14 de febrero a la madrugada.

![](image.png)

Bajón, man.

#### Anexo Git

Modificar el mensaje de uno o más commits después de haber realizado un push:

```zsh 
» git rebase -i HEAD~6 # List of the last n commits
```
- Reemplazar `pick` por `reword`

```zsh
» pick b5a9997 Upload image: caffetiera.png
```
```zsh
» reword b5a9997 Upload image: caffetiera.png
```
- Guardar y cerrar

```zsh
Upload image: caffettiera.png # New commit message
```
- Volver a guardar y cerrar

```zsh
» git push --force origin master # Force-push amended commits
```