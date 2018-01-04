### git tag nombre_etiqueta (Etiquetas Ligeras).
Etiqueta simple, no contiene una descripción sobre el commit al que se le asigna.

### git tag -a nombre_etiqueta -m "mensaje de la etiqueta" (Etiquetas Anotadas).
Etiqueta anotada. Se guarda en la base de datos de Git como un objeto entero. Tiene un checksum; contiene el nombre del etiquetador, correo electrónico y fecha; y tienen un mensaje asociado.

### git show nombre_etiqueta.
Enlista alfabéticamente las etiquetas que contiene nuestro repositorio.

```
git tag -l "v1.*"
```
Lista las etiquetas que coincidan con el patrón especificado.
