# Fundamentos del desarrollo de videojuegos
## Práctica 1.1
### Diego Herrera Mendoza
Git LFS

1. Crea una carpeta  que incluya 2 imágenes y 3 ficheros de texto. La utilizaremos para crear un repositorio Git que se conecte a GitHub. Puedes utilizar comandos o una herramienta visual. Las imágenes deben tener seguimiento LFS. Añade una imagen adicional y un fichero adicional y actualiza el repositorio GitHub con la nueva versión del proyecto.

Creamos el repositorio Git a partir de la carpeta local actual.
```
git init
```

Las imágenes y los textos añadidos son de Google.

Habilitamos Git LFS en el repositorio con el comando:
```
git lfs install
```

Indicamos a Git LFS que debe gestionar los ficheros con extensión jpg y txt.
```
git lfs track *.jpg
git lfs track *.txt
```
---

2. Crea un repositorio Git LFS para el proyecto Unity de la tarea 1.2. Configura el fichero .gitattribute adecuado. Una segunda versión del fichero debe incluir una textura y un segundo script que muestre el mensaje en consola "Script tarea 1.2". Obtener capturas de pantalla del proceso para realizar la entrega de la práctica.

[Enlace al repositorio](https://github.com/DiegoHerrera2/FDV2)

![gitattributes](images/atributes.png)

- [.gitignore](https://github.com/DiegoHerrera2/FDV2/blob/main/.gitignore)
- [.gitattributes](https://github.com/DiegoHerrera2/FDV2/blob/main/.gitattributes)


- [Textura](https://github.com/DiegoHerrera2/FDV2/blob/main/Assets/texture.jpg)
- [Script](https://github.com/DiegoHerrera2/FDV2/blob/main/Assets/Message.cs)

---

