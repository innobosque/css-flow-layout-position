# POSITION RELATIVE

```
elemento{
	position:relative;
}
```

Cuando a un elemento le añadimos la __propiedad relative__: 
- EN PRINCIPIO NO PASA NADA VISUALMENTE (Es decir, en principio no se nos desmaqueta nada)
- INTERNAMENTE SÍ	

Pero ya podemos manipular sus coordenadas (top,left,bottom,right) o z-index
- Coordenadas en cuanto a la disposición inicial del elemento
- Si lo movemos el espacio se conserva y no se pierde (__el espacio se queda reservado__)

## CONDIDERACIONES IMPORTANTES

### ALTURA
- La altura se define según el contenido
- Si trabajamos con porcentajes quién toma de referencia???
	- Toma de referencia al padre
		- Problema cuando el padre no tiene un alto definido (min-height)
		- top,bottom no funciona (en cambio el ancho funciona en cambio perfectamente con left y right)
- PUNTO CERO CERO (X,Y)
	- SIMPRE DONDE ESTÉ POSICIONADO ACTUALMENTE

[volver](README.md)