# LIBRERÍA DE VALIDACIÓN DE DAW2

Version 1.7.

## Descripción
Clase de validacion de formularios que contiene las funciones necesarias para validar los campos de un formulario.

## Requisitos
>PHP version 7.0 o superior.

>Extensión mbstring, instalamos el módulo phpX.X-mbstring según la versión de php que tengamos.

## Versiones
>1.7 13/12/2025 Añadidas funciones comprobarFloatMonetarioES() y comprobarCadenaEspecifica(). Modificación funciones comprobarMaxTamanio() y comprobarMinTamanio().

>1.6 30/11/2020 Mejoras en las funciones comprobarEnter(), comprobarFloat(), validarPassword().

>1.5 mejorada la ortografía de los mensajes de error se escribian cada vez que querías mostrarlos ahora ya los devuelve cada función a la que se ha llamado sin tener que escribir nada.

>1.4 Mejorado los métodos comprobarEntero() y comprobarFlaoat() comprobarAlfanumerico y validarEmail. También he eliminado una función inservible "comprobarCódigo". Este cambio se basa en simplificar la cantidad de código ya que antes los>errores.

>1.3 Se han modificado la devolución de varias funciones: comprobarNoVacío, comprobarMintamanio, comprobarMaxTamanio, comprobarEntero, comprobarFloat, antes estas 3 devolvían un valor boolean, ahora devuelven una cadena con el mensaje de error. Estas 3 anteriores funciones se emplean en otras 3 funciones que he cambiado, algo más compuestas las cuales son: comprobarAlfabético.

>1.2 Se han acabado de formatear los mensajes de error, se han modificado validarURL() y se han añadido validarCp(), validarPassword(), validarRadioB() y validarCheckBox().

>1.1 Se han formateado los mensajes de error y modificado validarDni().

## Reconocimiento
Creada por alumnos del IES Los Sauces.

>Version 1.7 Véro Grué y Gonzalo Junquera.

>Version 1.6 Javier Nieto y Cristina Nuñez.

>Versión 1.3 Adrián Cando Oviedo.

@copyright 2018-2025 DAW2.
