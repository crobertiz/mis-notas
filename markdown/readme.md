# Markdown

## Tabla de contenido

- [Para empezar](#para-empezar)
- [Encabezados](#encabezados)
- [Énfasis](#énfasis)
- [Listas](#listas)
- [Enlaces](#enlaces)
- [Cita](#cita)
- [Linea Horizontal](#linea-horizontal)
- [Código](#código)
- [Tabla](#tabla)
- [Imagen](#imagen)
- [Github Markdown](#github-markdown)
  - [Lista de tareas](#lista-de-tareas)
  - [Mencionar a alguien](#mencionar-a-alguien)
  - [Emojis](#emojis)

## Para empezar

[Wikipedia](https://es.wikipedia.org/wiki/Markdown)

[Hoja de trucos](https://www.markdownguide.org/cheat-sheet/)

> Ctrl + Shift + V para vista previa en vscode

Para dar saltos de línea deje una línea entre cada uno

## Encabezados

```md
# my title h1

## my title h2

### my title h3

#### my title h4

##### my title h5

###### my title h6

standar
```

# my title h1

## my title h2

### my title h3

#### my title h4

##### my title h5

###### my title h6

standar

## Énfasis

```md
_Italic type_
**Bold**
~~Negative~~
```

_Italic type_

**Bold**

~~Negative~~

## Listas

### Listas ordenadas

```md
1. apple
2. orange
3. purple
```

1. apple
2. orange
3. purple

### Listas desordenadas

```md
- apple
- orange
- purple
```

- apple
- orange
- purple

## Enlaces

### Enlaces a sitios externos

```md
[Google](https://google.com)
```

[Google](https://google.com)

### Enlaces a encabezados

```md
[Ir a Página web](#pagina-web)
```

[Ir a Página web](#pagina-web)

## Cita

```md
> Take your time
```

> Take your time

## Linea Horizontal

```md
---
```

---

## Código

### En linea

```md
`console.log('Hola mundo')`
```

`console.log('Hola mundo')`

### De bloque

````md
```js
const name = ["Alvaro", "Jose", "Maria"];

if (name[0] === name[1]) {
  console.log("Yes");
}
```
````

```js
const name = ["Alvaro", "Jose", "Maria"];

if (name[0] === name[1]) {
  console.log("Yes");
}
```

## Tabla

```md
| Fruits | Price |
| :----- | :---- |
| Apple  | 1$    |
| Grapes | 4$    |
| Orange | 2$    |
| Lemon  | 1$    |
| Peach  | 3$    |
| Melon  | 20$   |
```

| Fruits | Price |
| :----- | :---- |
| Apple  | 1$    |
| Grapes | 4$    |
| Orange | 2$    |
| Lemon  | 1$    |
| Peach  | 3$    |
| Melon  | 20$   |

## Imagen

```md
![vscode](https://images.unsplash.com/photo-1648737155328-0c0012cf2f20?ixlib=rb-1.2.1&ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80 "Title Image")
```

![Steve Jobs](https://images.unsplash.com/photo-1648737155328-0c0012cf2f20?ixlib=rb-1.2.1&ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80 "Title Image")

## Github Markdown

Esto solo funciona en github

### Lista de tareas

```md
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
- [x] Task 4
```

- [x] Task 1
- [ ] Task 2
- [ ] Task 3
- [x] Task 4

### Mencionar a alguien

@crobertizdev

### Emojis

[Github emojis](https://gist.github.com/rxaviers/7360908)

```md
:kissing:
```

:kissing:
