# Documentación del proyecto CEyED

para hacer páginas de documentación:

```bash
-src
    -content
        -docs
            -<nombre-carpeta> ( Puedes crear una nueva mientras sigas la estructura de ejemplo de la carpeta "Ejemplo")
                -index.mdx (página principal donde se mostrará el contenido de la carpeta)
                -<nombre-archivo>.mdx (páginas secundarias que se mostrarán en la página principal)
```

ejemplo del directorio: 

---

![image](https://github.com/user-attachments/assets/1ee9c7d6-5184-47e4-9528-2349f50b6752)

ejemplo index.mdx:

---

![image](https://github.com/user-attachments/assets/c5e76330-5717-48bd-a7d6-9cbf837cb499)

ejemplo <nombre-archivo>.mdx:

---

![image](https://github.com/user-attachments/assets/347760f5-5a76-4e25-a0cb-f7d90805e018)

---

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

