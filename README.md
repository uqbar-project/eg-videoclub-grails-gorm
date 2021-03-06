# Videoclub en Grails - con GORM

![demo](https://github.com/uqbar-project/eg-videoclub-ui-grails/blob/master/video/demo-videoclub.gif)

## Explicación

Pantalla para alquilar películas que se divide en varias partes, de manera que el cliente pueda disparar pedidos asincrónicos (vía AJAX | jQuery-UI). 

**Ventajas:** se puede filtrar las películas a medida que se va completando el campo, sin necesidad de traer todas las películas al cliente. No se refresca toda la página cuando se busca una película, se selecciona o bien cuando se agrega o elimina una película al pedido.

## Consideraciones

* El objeto de dominio está construido con GORM (Grails Object/Relational Mapping)
* También el service que maneja las transacciones
* Los controllers y las vistas son propias de Grails

## Versión del proyecto de Grails

* Grails 2.4.2
* en un entorno GGTS 3.6.0
* con Twitter Boostrap 3.2.0

