# TEMA 6: DOCUMENTACIÓN Y CONTROL DE VERSIONES

## DOCUMENTACIÓN CON MARKDOWN


### Cabeceras

```markdown
# Esto es una cabecera de nivel 1 
## Esto es una cabecera de nivel 2 
### Esto es una cabecera de nivel 3
```

---
# Esto es una cabecera de nivel 1 
---
## Esto es una cabecera de nivel 2
---
### Esto es una cabecera de nivel 3
---


### Listas sin orden

```markdown
- Elemento 1
- Elemento 2
- Elemento 3
    - Subelemento 1
    - Subelemento 2
```
- Elemento 1
- Elemento 2
- Elemento 3
    - Subelemento 1
    - Subelemento 2


### Lista con orden

```markdown
1. Elemento 1
2. Elemento 2
3. Elemento 3
    - Subelemento 1
    - Subelemento 2
```
1. Elemento 1
2. Elemento 2
3. Elemento 3
    - Subelemento 1
    - Subelemento 2


### Formato

```markdown
*Este texto se muestra en itálica*

_Este también se mostrará en itálica_

**Este texto se muestra en negrita**

__Este también se mostrará en negrita__

*Puedes **combinar** ambos formatos*

Puedo ~~tachar~~ el texto 
```
*Este texto se muestra en itálica*

_Este también se mostrará en itálica_

**Este texto se muestra en negrita**

__Este también se mostrará en negrita__

*Puedes **combinar** ambos formatos*

Puedo ~~tachar~~ el texto


### Enlaces

```markdown
[GitHub](http://github.com)
```
[GitHub](http://github.com)


### Imágenes

```markdown
![GitHub Logo](/images/logo.png)

Formato: ![Texto alternativo](url)
```
![Velez_Logo](https://github.com/alvarodelmoral/Apuntes-Markdown/blob/master/velez.png)


### Citas

```markdown
Como dijo Aragorn:

> No es oro todo lo que reluce
> ni toda la gente errante anda perdida
```
Como dijo Aragorn:

> No es oro todo lo que reluce
> ni toda la gente errante anda perdida


### Tablas 

```markdown
| Modelo | Color   | Precio |
| ------ |---------| ------:|
| Globe  | Negro   | 99€    |
| Scala  | Azul    | 199€   |
| Palais | Granate | 399€   |
```
| Modelo | Color   | Precio |
| ------ |---------| ------:|
| Globe  | Negro   | 99€    |
| Scala  | Azul    | 199€   |
| Palais | Granate | 399€   |


### Bloques de código

```markdown
$(function(){
    $('div').html('Hola, mundo');
  });
```
$(function(){
    $('div').html('Hola, mundo');
  });
  
  
  
  
## CONTROL DE VERSIONES


### Instalación de git

```bash
sudo  apt  install  git
```


### Configuración de git

```bash
git  config  --global  user.name   "Nombre y Apellidos"
git  config  --global  user.email  "nombre@mail.com"
```


### Iniciar repositorio local

```bash
git  init
```

Note: Es recomendable crear un archivo `.gitignore` con listado de carpetas y archivos a los que no se realizará seguimiento.


### Comandos básicos

```bash
git  status
git  add .
git  commit -m  "Mensaje"
```


### Clonar repositorio remoto 

```bash
git  clone   https://github.com/usuario/repositorio.git
git  clone   git@github.com:usuario/repositorio.git
```


### Vincular y desvincular repositorio remoto

```bash
git  remote  -v
git  remote  add  origin  https://github.com/usuario/repositorio.git
git  remote  rm   origin
```


### Bajar y subir contenido a repositorio remoto

```bash
git  pull  origin  master  // bajar commits
git  push  origin  master  // subir commits
```


###  Trabajo con ramas

```bash
git  branch    -va        // listado verbose, all (local y remoto)

git  branch    nuevo      // creación de rama
git  checkout  nuevo      // cambiar a dicha rama

git  checkout  -b nuevo   // equivalente a las 2 sentencias anteriores
```


### Checkout

- El comando **`checkout`** de `git` sirve para **cambiar de rama**.

```bash
git  checkout  rama
```

- También sirve para **cambiar de commit dentro de una rama**.

```bash
git  checkout  0f82
```


### Etiquetas de anotación

```bash
git tag -l                          // Listado
git tag -a v1.0 -m "Version 1.0"    // Añadir etiqueta
git tag -d v1.0                     // Eliminar etiqueta
```

- Las etiquetas deben enviarse explícitamente al repositorio remoto:

```bash
git  push  --tags
```

