---
title: 'Mi Chuleta de Markdown'
description: 'Guía de referencia rápida para escribir en Markdown'
pubDate: 'Jun 12 2026'
heroImage: '../../assets/blog-ph1-jam-stdio.png'
---

# Guía Completa de Markdown

Markdown es un lenguaje de marcado ligero que permite dar formato a texto plano de forma sencilla y legible. Es ampliamente utilizado en documentación, README de proyectos, blogs y plataformas como GitHub o Notion.

---

## Índice

1. [Encabezados](#encabezados)
2. [Énfasis y estilos de texto](#énfasis-y-estilos-de-texto)
3. [Listas](#listas)
4. [Enlaces e imágenes](#enlaces-e-imágenes)
5. [Código](#código)
6. [Citas](#citas)
7. [Tablas](#tablas)
8. [Líneas horizontales](#líneas-horizontales)
9. [Saltos de línea y párrafos](#saltos-de-línea-y-párrafos)
10. [HTML embebido](#html-embebido)

---

## Encabezados

Se crean con el símbolo `#`. Cuantos más `#`, menor es el nivel del encabezado.

```
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6
```

> **Consejo:** Deja siempre un espacio entre el `#` y el texto.

---

## Énfasis y estilos de texto

| Estilo | Sintaxis | Resultado |
|---|---|---|
| Negrita | `**texto**` o `__texto__` | **texto** |
| Cursiva | `*texto*` o `_texto_` | *texto* |
| Negrita y cursiva | `***texto***` | ***texto*** |
| Tachado | `~~texto~~` | ~~texto~~ |
| Código en línea | `` `texto` `` | `texto` |

---

## Listas

### Lista desordenada

Usa `*`, `-` o `+` seguido de un espacio:

```
- Primer elemento
- Segundo elemento
  - Subelemento (indentado con 2 espacios)
  - Otro subelemento
- Tercer elemento
```

**Resultado:**
- Primer elemento
- Segundo elemento
    - Subelemento
    - Otro subelemento
- Tercer elemento

### Lista ordenada

Usa números seguidos de un punto:

```
1. Primer paso
2. Segundo paso
3. Tercer paso
```

### Lista de tareas

```
- [x] Tarea completada
- [ ] Tarea pendiente
- [ ] Otra tarea pendiente
```

---

## Enlaces e imágenes

### Enlace

```
[Texto del enlace](https://www.ejemplo.com)
[Enlace con título](https://www.ejemplo.com "Título opcional")
```

### Enlace de referencia

```
[texto][referencia]

[referencia]: https://www.ejemplo.com
```

### Imagen

La sintaxis es igual que un enlace pero con `!` al inicio:

```
![Texto alternativo](ruta/a/imagen.png)
![Logo](https://ejemplo.com/logo.png "Título opcional")
```

---

## Código

### Código en línea

Rodea el texto con comillas invertidas:

```
Usa la función `print()` para mostrar texto.
```

### Bloque de código

Usa tres comillas invertidas (`` ``` ``), opcionalmente seguidas del nombre del lenguaje para resaltado de sintaxis:

````
```python
def saludar(nombre):
    print(f"Hola, {nombre}!")

saludar("Mundo")
```
````

```python
def saludar(nombre):
    print(f"Hola, {nombre}!")

saludar("Mundo")
```

Lenguajes soportados habituales: `python`, `javascript`, `bash`, `html`, `css`, `json`, `sql`, `java`, `go`, etc.

---

## Citas

Usa `>` al inicio de la línea:

```
> Esto es una cita.
>
> Puede tener varios párrafos.
>> Cita anidada.
```

> Esto es una cita.
>
> Puede tener varios párrafos.
>> Cita anidada.

---

## Tablas

Las columnas se separan con `|` y la fila de encabezado se separa del cuerpo con `---`:

```
| Nombre   | Edad | Ciudad    |
|----------|------|-----------|
| Ana      | 28   | Madrid    |
| Carlos   | 34   | Barcelona |
| Laura    | 22   | Sevilla   |
```

| Nombre   | Edad | Ciudad    |
|----------|------|-----------|
| Ana      | 28   | Madrid    |
| Carlos   | 34   | Barcelona |
| Laura    | 22   | Sevilla   |

### Alineación en tablas

```
| Izquierda | Centro | Derecha |
|:----------|:------:|--------:|
| texto     | texto  | texto   |
```

| Izquierda | Centro | Derecha |
|:----------|:------:|--------:|
| texto     | texto  | texto   |

---

## Líneas horizontales

Usa tres o más guiones, asteriscos o guiones bajos en una línea:

```
---
***
___
```

---

## Saltos de línea y párrafos

- Para crear un **nuevo párrafo**, deja una línea en blanco entre bloques de texto.
- Para un **salto de línea** dentro del mismo párrafo, añade dos espacios al final de la línea o usa `\` (dependiendo del renderizador).

---

## HTML embebido

En la mayoría de renderizadores, puedes usar HTML directamente:

```html
<details>
  <summary>Haz clic para expandir</summary>
  Contenido oculto aquí.
</details>

<br> <!-- Salto de línea -->

<mark>Texto resaltado</mark>
```

---

## Notas finales

- El soporte exacto de características varía según la plataforma (GitHub, VS Code, Obsidian, etc.).
- La especificación más extendida es [CommonMark](https://commonmark.org/).
- GitHub usa su propio sabor llamado **GFM** (*GitHub Flavored Markdown*) que añade tablas, listas de tareas y más.

---

*Guía creada con ❤️ en castellano.*
