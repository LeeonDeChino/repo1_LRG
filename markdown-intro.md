# _MarkDown_

_MarkDown_ es un lenguaje de marcado que sirve para definir contenido. Es muy usado para documentar proyectos de _software_. Es el estándar en el que se redacta la documentación. También es utilizado para crear contenido estático que posteriormente se pueda compilar a código _HTML_.

## Índice de contenido

- [Introducción](#markdown).
- [Comandos](#comandos).
- [Párrafos](#párrafos).
- [Negritas y cursivas](#negritas-y-cursivas).
- [Encabezados](#negritas-y-cursivas).
- [Imágenes](#imágenes).
- [Links](#links).
- [Divisiones](#divisiones).
- [Listas](#links).
- [Citas](#citas).
- [Tablas](#tablas).
- [Código](#código).
- [Comentarios](#comentarios).
- [Escape de caractéres](#escape-de-caractéres).

## Comandos

 _**Alt + Shift + Up/Down**_  = Copiar la línea de texto arriba o abajo

_**Alt + Up/Down**_ = Mover la línea de texto arriba o abajo.

_**Alt + Shift + A**_ = Comentar lo seleccionado.

## Párrafos
Un párrafo es una extensión de texto que finaliza cuando hay un salto de línea (enter) en el documento.

Este sería el párrafo 2.

## Negritas y cursivas
En Markdown podemos escribir en negritas utilizando asteriscos: **negritas**

Para cursivas, lo mismo pero con guión bajo: _cursivas_

Combinando: _**negrita y cursiva**_

## Encabezados

# Encabezado H1

## Encabezado H2

### Encabezado H3

#### Encabezado H4

##### Encabezado H5

###### Encabezado H6

## Imágenes

![Profile Picture](./IMG/PP2.webp)

![Imagen Random](https://pic2-cdn.creality.com/crealityCloud/common/62dc2de9195304ee3c444ec43b8cd27e.jpeg)

Imagen con link
[![Imagen Random](https://www.riotgames.com/darkroom/1440/659ad672084360e550482dc6c1269f88:17c9007e1ee11ff36db2cd1cd1413169/marquee-raze-thumb.png)](https://www.youtube.com/watch?v=dPEtlMFvtFA&pp=ygUQaG93IHRvIG1haW4gcmF6ZQ%3D%3D)

## Links

[YouTube](https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs)

[Ir al encabezado 1](#encabezado-h1)

[Ir al archivo comandos.txt](./comandos.txt)

## Divisiones

---

Esta es otra sección, la línea de arriba se llama **división**


## Listas

### Listas desordenadas
  - Primavera
  - Verano
  - Otoño
  - Invierno

### Listas ordenadas
1. Primavera
1. Verano
1. Otoño
1. Invierno

### Listas anidadas
- Primavera
  - Abril
  - Mayo
  - Junio
    - Mi cumpleaños
- Verano
  - Julio
  - Agosto
  - Septiembre
    - Mes patrio
- Otoño 
  - Octubre
    - Jaguelin
  - Noviembre
  - Diciembre
    - Navidad
- Invierno
  - Enero
    - Año Nuevo
  - Febrero
  - Marzo

  ## Citas

  ### Cita en una línea
  > Yo sólo sé, que no sé nada.

  ### Cita en bloque
  > Todo lo que escuchamos, es una opinión.
  > Todo lo que vemos es una perspectiava, no la verdad.
  >
  > -Marco Aurelio

  ## Tablas

  | País | Ciudad | Continente |
  | - | - | - |
  | México | CDMX | América |
  | Japón | Tokyo | Asia |

## Código

### Bloques de código
```js
function sumar (a,b){
  if(){

  }
}
```

```c
function sumar (a,b){
  if(){

  }
}
```

### Código HTML - Barra de búsqueda

<form>
<label for = "q">Buscar:</label>
<input type ="search" name ="q" id="q" required />
<input type ="submit" value="🔎"/>
</form>

---

## Comentarios

Alt+Shift+A = comentar

<!-- Esto es un comentario -->

## Escape de caractéres

La contrabarra (\\) sirve para omitir el efecto de los caractéres como asterisco y guión bajo 

Texto en: \_cursiva\_

Texto en: \*\*negritas\*\*

  [☝🏼Regresar](#markdown)