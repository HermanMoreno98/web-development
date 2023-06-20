# Curso de desarrollo web

## Inicializar git

```
git init
```

## Configurando git con GitHub

```
git config --global user.email <Enter_your_email>
git config --global user.name <Enter_your_user_name_on_GitHub>
```

## Coenxion remota con GitHub
```
git remote add origin  <REMOTE_URL>
```

## Para verificar si esta conectado con GitHub
```
git remote -v
```

## Verificar los archivos creados/modificados/eliminados en la dirección indecada
```
git status
```

## Agregando todos los cambios al stage
```
git add .
```

## Commiteando los cambios
```
git commit -m <Nombre_del_commit>
```

## Agregando todos los commits a GitHub
```
git push origin <Nombre_de_rama_creada>
```

## Para descargar los cambios remotos a mi local. En este caso, de github.com
```
git pull origin main
```

## Para descargar algun proyecto de github a mi pc (siempre y cuando la repo sea pública)
```
git clone url_de_github
```

## Este comando sirve para poder listar los branch que tengo localmente y me dice en cuál me encuentro actualmente
```
git branch
```

## Creando nueva rama
```
git branch -b <Nombre_de_nueva_rama>
```

## Cambiando nombre a la rama
```
git branch -m <Nombre_de_rama>
```

## Cambiando entre ramas. 👁️ Si el checkout no tiene el -b, solamente es para moverse entre ramas
```
git checkout <Nombre_de_rama_a_cambiar>
```

## Para poder juntar o unir los cambios entre ramas
* Primero cambiar a la rama principal (main)
```
git checkout main 
```
* Unir los cambios de otra rama, a la principal
```
git merge <Nombre_de_nueva_rama>
```
* Después de verificar que se encuentran los cambios, se debe subir a github
```
git push origin main
```

## Eliminando rama creada en local
```
git brandh -d <Nombre_de_rama_eliminar>
```

## Actualiza cambios en la rama pero referente a nuevas ramas locales
```
git fetch
```
