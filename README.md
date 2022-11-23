# Flow Layout

## Table of contents

- [Overview](#overview)
- [Definición](#definición)
- [Valores](#valores)
  - [Por defecto](#por-defecto)
  - [Elementos posicionados](#elementos-posicionados)
	- [Propiedades](#propiedades)

## Overview

### Conceptos iniciales (Flow Layout)

- __Flujo (flow)__:	orden en que aparecen los elementos en el HTML
- __Romper el flujo__: cuando modificamos el orden normal en que aparecen un html. Ejemplos:
	- float: none
	- display: flex
	- position: absolute
- __Espacio ocupado__:Espacio que ocupa un elemento en ese flujo. Ese espacio en ocasiones se RESERVA y en ocasiones NO:
	- display:none  
	- visibility:hidden

## Definición

Se trata de una __propiedad__ que nos permite controlar la posición de un elemento en el flujo (flow) normal de los elementos que se colocan en el HTML

## Valores

### Por defecto

static (default): __No se considera posicionado__

```html
.btn{
	posistion: static;
}
```
Observamos que como resultado no pasa nada. Simplemente está posicionado en el elemento que le corresponde, NO ESTÁ POSICIONADO.
__¿Para qué la existencia de este atributo?__
Eventos: Javascript, :hover (Ejemplo con top)

### Elementos posicionados	

1. [relative](relative.md)
2. [absolute](absolute.md)
3. [fixed](fixed.md)
4. [sticky](sticky.md)

### Superposición

[z-index](z-index.md)

### Propiedades
Todo elemento posicionado (NO FUNCIONA CON static) adquieren automáticamente cuatro propiedades nuevas (coordenadas):
			
- top (coordenada superior)
- right (coordenada derecha)
- bottom (coordenada inferior)
- left (coordenada izquierda) 
		
Hay una quinta propiedad que sirve para elementos superpuestos

- z-index