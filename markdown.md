# Tasca1.1 Markdown y Github
### Headers
·Los headers son formatos que se le puede aplicar a un documento escrito en markdown # header #.Su función es crear una cabezera con el comando "#". Según el número de "#" es más grande o más pequeña la cabezera. Hay 6 tipos de cabezeras. Desde # (cabezera más grande) hasta ###### (cabezera más pequeña de todas).
Ejemplo:
# header con "#"
## header con "#"
### header con "###""
#### header con "####"
##### header con "#####"
###### header con "######"
    
### Emphasis
·Las emphasis son formatos que se le pueden aplicar al texto. Como la cursiva, negrita o subrayar el texto
Ejemplos:
Ejemplo de cursiva: *hola mundo*        Comando ```*hola mundo*```
Ejemplo de negrita: **hola mundo**      Comando ```**hola mundo**``` o ```__hola mundo__```
Ejemplo de combinar las emphasis (negrita y cursiva): **_mundo_** Comando ```**_hola mundo_**```
Ejemplo de subrayado: ~~hola mundo~~ comando: ```~~hola mundo~~```
### List
Los list sirven para poder hacer lista en un documento en markdown, estas lista pueden tener sublista.
Ejemplos de lista:
Ejemplo de código:
1.Agua 
2.Pan
3.Carne
..*Sublista de carne desordenada
4-Pescado
..4.Sublista de pescado ordenada
...Puedes tener párrados dentro de los elementos de la lista.
...Para tener un salto de línea sin párrados,se usará dos "enter".
*La lista desordenada puede usar asteriscos
- o menos
+ o más

### Links
 
 La función principal de Links es poder añadir una URL y direccionarte a esa dirección. Se puede hacer de dos formas:
 Comando: ```[Link 1 de Google](https://www.google.com)``` Resultado: [Link 1 de Google](https://www.google.com)
 
 Comando: ```[Link 1 de Google](https://www.google.com "Página principal de Google)``` Resultado: Si dejas el cursor en el link te sale Página principal de Google [Link 1 de Google](https://www.google.com "Página principal de Google")
 Comando: ```[Link relativo referente a repositorio](../blob/master/LICENSE)``` Resultado:[Link relativo referente a repositorio](../blob/master/LICENSE)
 Puedes usar números para los links. Se usa siempre la ruta entera oara hacer un link.
### Images
La función de Images es simplemente incluir imágenes al archivo.
Comando: ```Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")``` Resultado: Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
### Code and Syntaz Highlighti
Su función es poder procesar todos los signos especiales de cada lengua para que los pueda interpretar.
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
var s = "JavaScript syntax highlighting";
alert(s);
s = "Python syntax highlighting"
print s
### Tables
Las tablas no son parte de markdown pero las admite, son una forma sencilla de agregar tablas a tu correo, hacer una tarea.
Comando:
```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

### Blockquotes
Los blockquotes son muy útiles en el correo electrónico para emular el texto de respuesta.
Ejemplo:
```
> Soy Jose Quesada.
> Hola como estás?.
Cuota descanso.
> Hola, estoy muy bien, cuando nos vemos?
```
Resultado:
> Soy Jose Quesada.
> Hola como estás?
Respuesta:
> Hola, estoy muy bien, cuando nos vemos?
### Inline HTML
Puedes usar HTML sin formato en su Markdown y funcionará bien.
Ejemplo:
```
<dl>
  <dt>Lista compra</dt>
  <dd>pan</dd>
  <dd>agua</dd>
  <dd>carne</dd>
  <dt>Markdown en HTML</dt>
  <dd>No*funcionan* las emphasis de **Markdown**. Usa los <em>tags</em> de HTML.</dd>
</dl>
```
### Que codificación de caraacteres tiene este fichero?
La codificación es UTF-8

### Funciones de git: como funciona
**Clone**: Crea un cópia de un repositorio remoto
**Add**: Hace una instantánea de los ficheros para versionarlos, añadiendolos al index.
**Commit**: Guarda la instantáneas de los ficheros permanentemente al historial de versiones.
**Push**: Carga todos los ficheros validados de la rama local al repositorio remoto.
**Pull**: Descarga y incorpora los cambios des del repositorio remomto.