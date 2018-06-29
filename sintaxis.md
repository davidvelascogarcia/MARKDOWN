# Lenguaje de marcado: Markdown

- [Tablas](#tablas)
- [Listas de tareas](#listas-de-tareas)
- [Encabezados](#encabezados)
- [Fuentes](#fuentes)
	- [Cursivas](#cursivas)
	- [Negrita](#negrita)
	- [Negrita y cursiva](#negrita-y-cursiva)
- [Links](#links)
- [Imágenes](#imágenes)
- [Desplazamiento entre directorios](#desplazamiento-entre-directorios)
- [Menciones de usuario](#menciones-de-usuario)
- [Comentarios de código](#comentarios de código)
- [Índices y puntos](#índices-y-puntos)
- [Índices con hiperenlaces](#índices-con-hiperenlaces)

## Tablas

Ejemplo de tablas.

| Elemento 1 | Elemento 2 | Elemento 3 |
| ---------- | ---------- | ---------- |
| Elemento 1 | Elemento 2 | Elemento 3 |
| Cosa 1| Cosa 2|COsa3|cosa|

Código:

```markdown

| Elemento 1 | Elemento 2 | Elemento 3 |
| ---------- | ---------- | ---------- |
| Elemento 1 | Elemento 2 | Elemento 3 |
| Cosa 1| Cosa 2|Cosa 3|
```

## Listas de tareas

Ejemplo lista de tareas.

- [ ] Elemento 1
- [ ] Elemento 2
- [ ] Elemento 3

Código:

```markdown
- [ ] Elemento 1
- [ ] Elemento 2
- [ ] Elemento 3

```

## Encabezados

Ejemplo de encabezados.

# Nivel 1
## Nivel 2
### Nivel 3
### Nivel 4

Código:

```markdown
# Nivel 1
## Nivel 2
### Nivel 3
### Nivel 4

```

## Fuentes

Configuración sobre las fuentes de texto.

### Cursivas

Ejemplo de cursivas.

*Mensaje de prueba*

Código:

`*Mensaje de prueba*`


### Negrita

Ejemplo de negrita.

**Mensaje de prueba**

Código:

`**Mensaje de prueba**`


### Negrita y cursiva


Ejemplo de negrita y cursiva.

***Mensaje de prueba***

Código:

`***Mensaje de prueba***`

## Links

Ejemplo de link.

[link](www.google.es)

Código:

`[link](www.google.es)`

## Imágenes

Ejemplo de imágen.

![Nombre de la imagen en caso de no cargar](http://www.analiticaweb.es/wp-content/uploads/2017/02/markdown.jpg)

Código:

```markdown
![Nombre de la imagen en caso de no cargar](http://www.analiticaweb.es/wp-content/uploads/2017/02/markdown.jpg)
```
## Desplazamiento entre directorios

Ejemplo movimientos en ruta.

1. Adelante

Ejemplo adelante.

[nombre enlace](./ruta a ir)

Código:

```bash
[nombre enlace](./ruta a ir)
```

2. Atrás

Ejemplo atrás.

[nombre enlace](../)

Código:

```bash
[nombre enlace](../)
```

## Menciones de usuario

Menciones mediante `@nombredeusuario`
Ejemplo:

@davidvelascogarcia

## Comentarios de código

El comentario de código.

1.  En una línea.

* Si se trara de comentar un fragmento en una línea mediante apertura y cerrado del mensaje a comentar con `


Ejemplo:

`Mensaje a comentar`

Código:

```bash
`Mensaje a comentar`
```

2.  Varias líneas.

* Si se trara de comentar un fragmento en varias líneas mediante apertura y cerrado del mensaje a comentar con ```


Ejemplo:

```bash
Mensaje a comentar
```
## Índices y puntos

* Índices
Mediante:

1. Elemento 1
	1.Subelemto 1
	2.Subelemento 2
	1. Subsubelemento 1
2. Elemento 2
3. Elemento 3

Código:

```markdown
1. Elemento 1
	1.Subelemto 1
	2.Subelemento 2
	1. Subsubelemento 1
2. Elemento 2
3. Elemento 3
```

* Puntos
Mediante:

* Elemento 1
	* Subelemto 1
	* Subelemento 2
		*  Subsubelemento 1
* Elemento 2
* Elemento 3

Código:

```markdown

* Elemento 1
	* Subelemto 1
	* Subelemento 2
		*  Subsubelemento 1
* Elemento 2
* Elemento 3

## Índices con hiperenlaces

- [Entrada 1](#entrada-1)
- [Entrada 2](#entrada-2)
- [Entrada 3](#entrada-3)
	-[Sub entrada 1](#sub-entrada-1)

## Entrada 1
## Entrada 2
## Entrada 3
### Sub entrada 1

Código:

```markdown


- [Entrada 1](#entrada-1)
- [Entrada 2](#entrada-2)
- [Entrada 3](#entrada-3)
	-[Sub entrada 1](#sub-entrada-1)

## Entrada 1
## Entrada 2
## Entrada 3
### Sub entrada 1

```
