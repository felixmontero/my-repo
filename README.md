# Iniciar un nuevo repositorio y publíquelo en GitHub.(EJERCICIO 2)
## Crear un nuevo directorio e inicialícelo con funciones específicas de git.
git init my-repo
## Cambiar al directorio `my-repo`.
cd my-repo
## Crear el primer archivo en el proyecto.
touch README.md
## Git no está al tanto del archivo, prepáralo.
git add README.md
## Tomar una instantánea del área de preparación
git commit -m "add README to initial commit"
## Proporcionar la ruta para el repositorio que creó en github.
git remote add origin https://github.com/felixmontero/my-repo/edit/master/.git
## Enviar cambios a github.
git push --set-upstream origin main
[![ACT2-PART-1.png](https://i.postimg.cc/fymfPjNG/ACT2-PART-1.png)](https://postimg.cc/9wX9R9zb)
[![ACT1-PART-2-2.png](https://i.postimg.cc/Y2R96LY0/ACT1-PART-2-2.png)](https://postimg.cc/7bCwD6Br)

# Contribuir a una rama existente en GitHub (EJERCICIO 3)

## Cambie al directorio `repo`.
cd repo
## Actualizar todas las sucursales de seguimiento remoto y la sucursal actualmente registrada.
git pull
## cambiar a la rama existente llamada `mi_rama`.
## Hacer cambios, por ejemplo, edite `file1.md` usando el editor de texto.
git add file1.md
## Tomar una instantánea del área de preparación.
git commit -m "Cambios en el archivo".
## Enviar cambios a github.
git push
[![Sin-t-tulo.png](https://i.postimg.cc/mZPLHpLX/Sin-t-tulo.png)](https://postimg.cc/23fNpwBh)
[![Sin-t-tulo1.png](https://i.postimg.cc/g0LsRP7c/Sin-t-tulo1.png)](https://postimg.cc/Ffm05wmw)
[![Sin-t-tulo2.png](https://i.postimg.cc/wMqDWKwm/Sin-t-tulo2.png)](https://postimg.cc/zbQLBQZz)
