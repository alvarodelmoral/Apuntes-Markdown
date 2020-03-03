# DOCUMENTACIÓN Y CONTROL DE VERSIONES

## Documentación con Markdown
### Cabeceras

```markdown
# Esto es una cabecera de nivel 1 (Titulo 1 <h1>)
## Esto es una cabecera de nivel 2 (Titulo 2 <h2>)
###### Esto es una cabecera de nivel 6 (Titulo 6 <h6>)
```

---
# Esto es una cabecera de nivel 1 (Titulo 1)
---
## Esto es una cabecera de nivel 2 (Titulo 2)
---
###### Esto es una cabecera de nivel 6 (Titulo 6)
---

### Listas sin orden

```markdown
- Item 1
- Item 2
    - Item 2a
    - Item 2b
```
- Item 1
- Item 2
    - Item 2a
    - Item 2b

### Lista con orden

```markdown
1. Item 1
2. Item 2
3. Item 3
    - Item 3a
    - Item 3b
```
1. Item 1
2. Item 2
3. Item 3
    - Item 3a
    - Item 3b

### Formato

```markdown
*Este texto se muestra en itálica*
_Este también se mostrará en itálica_

**Este texto se muestra en negrita**
__Este también se mostrará en negrita__

*Puedes **combinar** ambos formatos*
```
*Este texto se muestra en itálica*

_Este también se mostrará en itálica_

**Este texto se muestra en negrita**

__Este también se mostrará en negrita__

*Puedes **combinar** ambos formatos*


### Enlaces

```markdown
http://github.com - automático

[GitHub](http://github.com)
```
[GitHub](http://github.com)


### Imágenes

```markdown
![GitHub Logo](/images/logo.png)

Formato: ![Texto alternativo](url)
```
![GitHub Logo](https://github.com/josefilter/ApuntesMD/blob/master/descarga.png)


### Citas

```markdown
Como dijo Aragorn:

> No es oro todo lo que reluce
> ni toda la gente errante anda perdida
```
Como dijo Aragorn:

> No es oro todo lo que reluce
> ni toda la gente errante anda perdida


## Control de versiones


## Cabeceras (Títulos y subtítulos)

# Esto es un H1
## Esto es un H2
### Esto es un H3
#### Esto es un H4
##### Esto es un H5
###### Esto es un H6

Esto es un H1
Esto es un H2
Esto es un H3
Esto es un H4
Esto es un H5
Esto es un H6

Para las cabeceras de los dos primeros niveles también existe otra manera de hacer lo mismo:

Esto es un H1
=============
Esto es un H2
-------------
Esto es un H1
Esto es un H2
Texto plano y párrafos
Texto cualquiera, si al finalizar la linea colocamos dos espacios en blanco es un nuevo párrafo.

Texto normal.
Texto con 2 espacios al final.  
Texto normal.
Texto normal. Texto con 2 espacios al final.
Texto normal.

Viñetas y listas numeradas
- Elemento
- Elemento
- Elemento

1. Elemento
2. Elemento
3. Elemento
Elemento
Elemento
Elemento
Elemento
Elemento
Elemento
En lugar de - y 1. podemos utilizar * y 1) respectivamente:

* Elemento
* Elemento
    + Subelemento
        - Desagregación
* Elemento

1) Elemento
2) Elemento
3) Elemento
Elemento
Elemento
Subelemento
Desagregación
Elemento
Elemento
Elemento
Elemento
Formato
Para poner el texto en cursiva utilizamos * o _ antes y después del texto.
*cursiva* o _curvisa_
*curvisa o cursiva

Para poner el texto en negrita utilizamos ** o __ antes y después del texto.
**negrita** o __negrita__
negrita o negrita

Color
<span style="color:blue">Texto *rojo cursiva* normal</span>
Texto rojo cursiva normal

Superíndices
superindice^3^ 
superindice3

Tachado
~~tachado~~
tachado

Enlaces
<http://www.rusersgroup.com>
http://www.rusersgroup.com
