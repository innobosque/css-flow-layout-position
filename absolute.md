# POSITION ABSOLUTE

```
elemento{
	position:absolute;
}
```

## Consecuencias

- ESPACIO RESERVADO SE PIERDE (Cuidado que se se nos va a desmaquetar todo)
- El elemento se hace flexible. 
	- El tamaño del elemento es su contenido. Hay que dotarle de __width__ y __height__
- Podemos manipular sus coordenadas (top,left,bottom,right) o z-index

## CONDIDERACIONES IMPORTANTES

- ALTURA
	- La altura se define según el contenido
	- Si trabajamos con porcentajes quién toma de referencia
	- Toma de referencia al padre
	- No hay problema cuando el padre no tiene un alto definido (min-height)
- PUNTO CERO CERO (X,Y)
	- EL PRIMER ELEMENTO ANTECESOR POSICIONADO Y SI NO LO HAY BODY

[Volver](README.md)