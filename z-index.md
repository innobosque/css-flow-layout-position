# z-index

z-index Nos permite definir la posición en el eje z (profundidad o tres dimensiones) de un elemento POSICIONADO
	NO FUNCIONA SOBRE ELEMENTOS NO POSICIONADOS (todos los elemento tienen la propiedad static, o lo que es lo mismo NO ESTÁN POSICIONADOS)
	Si no utilizamos z-index los elementos posicionados se van poniendo uno por encima del otro en el orden en el que aparecen en el navegador
	Valores negativos pueden dar valores inesperados (sólo en ::before,::after)
	Buena práctica: dar valores altos


	::before,::after
		El elemento padre NO puede tener z-index
		Los valores de before y after tienen que ser 1 ó -1

[Volver](README.md)