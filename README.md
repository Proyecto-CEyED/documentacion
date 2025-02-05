# Documentación del proyecto CEyED

para hacer páginas de documentación:

-src
    -content
        -docs
            -<nombre-carpeta> ( Puedes crear una nueva mientras sigas la estructura de ejemplo de la carpeta "Ejemplo")
                -index.mdx (página principal donde se mostrará el contenido de la carpeta)
                -<nombre-archivo>.mdx (páginas secundarias que se mostrarán en la página principal)



ejemplo index.mdx:

ejemplo <nombre-archivo>.mdx:


# Instrucciónes para ejecutar el proyecto

git clone https://github.com/Proyecto-CEyED/documentacion.git
cd documentacion

## Instalar dependencias

```bash
npm install
```

## Ejecutar el proyecto en modo desarrollo

```bash
npm run dev
```

## Guardar cambios en el repositorio en una nueva rama

```bash
git checkout -b <nombre-rama>
git add .
git commit -m "Mensaje del commit"
git push origin <nombre-rama>
```

## Subir tu rama al repositorio

```bash
git checkout main
git pull origin main
git merge <nombre-rama>
git push origin main
```

