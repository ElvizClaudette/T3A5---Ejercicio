# T3A5---Ejercicio

## Etapa 1. Descripción del problema
Desarrolla una aplicación de cajero automático en Java en la cual se muestre un menú para
seleccionar la operación requerida por el usuario:

El usuario debe ingresar su tarjeta (número y NIP) para ingresar al menú principal, en caso
de que no coincida con sus datos entonces deberá mostrar una alerta donde le indique que sus
datos son erróneos.

- El menú principal debe tener las siguientes opciones:

1. Consultar saldo
2. Consultar estado de cuenta
3. Retirar efectivo
4. Otras opciones:
    - Seguros
    - Créditos
5. Salir

## Etapa 2. Diseño de la solución
- Entrada:
    - String numeroTargeta
    - int pin
    - float saldo
    - Adicionales nombre, email, telefono
- Proceso:
    - Validar los datos ingresados: numero de targeta y pin
    - Mostrar un menú de opciones del cajero automático 

- Salida:
~~~
+---------------------------------------------------------------+
|                           MENÚ                                |
+---------------------------------------------------------------+
~~~
