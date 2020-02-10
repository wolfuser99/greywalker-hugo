---
title: "Microservicios"
author: "Juan Antonio"
type: ""
date: 2019-09-20T20:43:44-03:00
subtitle: "Después de los monolitos..."
image: ""
tags: ["microservicios", "contenedores", "arquitectura"]
draft: false
---
Para comenzar, la **arquitectura de monolito** es la forma más común con que los sistemas informáticos o aplicaciones comienzan, ya que su baja complejidad y posterior escalamiento vertical en caso de que sea requerido, es sencillo.

**Por ejemplo:** pensemos en una aplicación para el control de inventario de un local comercial pequeño. Lo común en este caso sería crear una aplicación con algún Framework que permita a un pequeño numero de usuarios registrar los cambios en productos disponibles a una base de datos, luego tal vez ir agregando funcionalidades para: 

* control de materiales en bodega,
* registro desde múltiples sucursales,
* control de pago a proveedores,
* etc.

Y así con el aumento de funcionalidad ir escalando a una maquina con mayor capacidad de computo para que la aplicación no disminuya el rendimiento en los momentos de mayor demanda.
El siguiente paso común en la actualidad sería el salto al comercio online, donde nuestra arquitectura de monolito es más propensa a quedar estancada en momentos comerciales críticos como pueden ser los días de ofertas en que de un momento a otro la cantidad de usuarios puede superar los recursos de computo adquiridos para la aplicación. Es aquí donde entra en juego la **arquitectura de microservicios**.

<!--more-->
…


Esto es una prueba
que borraré, en algun momento.
{{% details "This is the details title (click to expand)" %}}
This is the content (hidden until clicked).
{{< figure src="/img/01.jpg" alt="test" >}}
{{% /details %}}