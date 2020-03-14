---
layout: page
title: Clase 3
description: Jueves (Mañana, 2020)
permalink: /bitacoras/2020/jueves-m/clase-03/
---

**¡Hola!**

Recordá que siempre es importante tener presente lo visto en la [clase anterior]({{site.baseurl}}/bitacora/jueves-m/clase-02) para poder consultarnos cualquier inquietud que te haya quedado.

Hoy además de continuar viendo algún otro __patrón de diseño__, cambiaremos un poco el enfoque de los problemas a los que nos enfrentamos. Hasta ahora venimos trabajando siempre con entidades que nosotros mismos creamos para resolver las problemáticas que se nos presentan, pero... ¿Qué pasa si tenemos que trabajar con entes que no conocemos? ¿Qué tanto nos conviene __acoplarnos__ a ellos? ¿Cómo podemos testearlos? ¿Qúe pasa si cambian su comportamiento?

_Importante: En caso de que tengas dudas sobre Java y Maven, ¡preguntá!_

# Resumen

- Aprenderemos sobre cómo introducir __interfaces entre componentes__.
- Veremos las diferencias entre los los diferentes tipos de interfaces: 
	- Entrantes vs. Salientes
	- Sincrónicas vs. Asincrónicas
- Trabajaremos en el _qué_ y _cómo_ __testear__ cuando interactuamos con servicios externos.
- Hablaremos sobre [__Code Ownership__](https://martinfowler.com/bliki/CodeOwnership.html).
- Conoceremos nuevos __patrones de diseño__:
	- State
	- Adapter

# Apuntes

- [Diseño de interfaces entre componentes](https://docs.google.com/document/d/1LurA-bCEHhCsIPFiFg1rqfIdfe5SdS4wBePfG45nDqg/edit#)
- [Patrones de Diseño - Patrón State](https://github.com/dieforfree/edsebooks/blob/master/ebooks/Design%20Patterns%2C%20Elements%20of%20Reusable%20Object-Oriented%20Software.pdf)
- [Patrones de Diseño - Patrón Adapter](https://github.com/dieforfree/edsebooks/blob/master/ebooks/Design%20Patterns%2C%20Elements%20of%20Reusable%20Object-Oriented%20Software.pdf)

# Material Complemetario

- [Video sobre testing de interfaces externas](https://www.youtube.com/watch?v=-p7_NUDLRB0&index=1&list=PLTpxfh7PF3OpJSMNNPaYxLJii3Xm7PPA_)
- [Mocks arent stubs](https://martinfowler.com/articles/mocksArentStubs.html)
- [Testing: todo lo que necesitás saber y más](https://docs.google.com/document/d/11mVR-4wEZhlQMDEqrfQeYLypEsrSqXv98dr78SA0Oq4)
- [Cualidades de las pruebas unitarias](https://docs.google.com/document/d/11mVR-4wEZhlQMDEqrfQeYLypEsrSqXv98dr78SA0Oq4)