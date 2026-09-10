# Laboratorio M1 – Sistema POS para Restaurante

Repositorio correspondiente al **Laboratorio M1 de Ingeniería de Software**, realizado para la asignatura de **Ingeniería de Software** de la Universidad de los Llanos.

## Información del proyecto

**Estudiante:** Johan Sebastian Jaime Patiño
**Código:** 160005339
**Programa:** Ingeniería de Sistemas
**Universidad:** Universidad de los Llanos – Unillanos
**Asignatura:** Ingeniería de Software
**Docente:** Olga Lucero Vega Marquez
**Año:** 2026

## Descripción

El proyecto presenta el análisis de un sistema POS para un restaurante de comida típica y almuerzos ejecutivos.

El objetivo es representar mediante **Casos de Uso (CDU)** las principales actividades que se realizan dentro del restaurante, incluyendo la atención de clientes, registro de pedidos, preparación de platos, cobros y administración.

Actualmente, el restaurante realiza gran parte de sus procesos de forma manual. Por esta razón, se plantea una representación del funcionamiento del negocio que permita identificar los actores involucrados y las principales funciones del sistema.

## Actores principales

El sistema contempla los siguientes actores:

* **Personal de Servicio:** registra pedidos, consulta disponibilidad, gestiona cancelaciones, calcula cuentas y recibe pagos.
* **Cocinero:** revisa los pedidos y prepara los platos solicitados.
* **Encargado:** administra la carta y consulta la información relacionada con las ventas.
* **Comensal:** participa en el proceso de pedido y pago.

## Casos de Uso

Los principales casos de uso definidos para el sistema son:

| Código | Caso de Uso              |
| ------ | ------------------------ |
| CU-01  | Registrar Pedido         |
| CU-02  | Verificar Disponibilidad |
| CU-03  | Anular Pedido            |
| CU-04  | Preparar Comida          |
| CU-05  | Obtener Total            |
| CU-06  | Registrar Cobro          |
| CU-07  | Administrar Carta        |
| CU-08  | Consultar Ventas         |

## Diagramas

Los diagramas de Casos de Uso fueron elaborados utilizando **Draw.io**.

La carpeta `diagramas` contiene los archivos correspondientes a los diferentes casos de uso del proyecto.

### Diagrama general

El diagrama general reúne los actores y las funciones principales del sistema, mostrando las relaciones entre el personal de servicio, cocinero, encargado y comensal.

## Relaciones UML utilizadas

Durante el desarrollo de los diagramas se utilizan principalmente:

* **Asociación:** representa la comunicación entre un actor y un caso de uso.
* **`<<include>>`:** indica que un caso de uso necesita ejecutar obligatoriamente otro.
* **`<<extend>>`:** representa un comportamiento adicional que puede ocurrir dependiendo de una situación.


## Herramientas utilizadas

* **Draw.io:** elaboración de los diagramas UML.
* **Git:** control de versiones.
* **GitHub:** almacenamiento y organización del proyecto.

## Objetivo académico

Este proyecto busca aplicar los conceptos vistos en Ingeniería de Software para analizar un proceso real de negocio, identificar sus actores y representar las principales funcionalidades mediante diagramas de Casos de Uso.

## Repositorio

Repositorio del proyecto:

**GitHub:** `johansebastianreinbor/lab4software`

---

**Ingeniería de Sistemas – Universidad de los Llanos**
**2026**
