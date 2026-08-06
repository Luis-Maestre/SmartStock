# 1. Introduction and Goals

## 1.1 Requierements Overview 

SmartStock ERP es un sistema ERP web orientado a pequeñas tiendas y negocios con inventarios de tamaño medio. Su propósito es optimizar la gestión de los movimientos de inventario mediante el registro centralizado de entradas y salidas de productos, permitiendo mantener un control actualizado del stock

Como valor diferenciador, el sistema incorpora un Sistema Inteligente de Reposición de Inventario, encargado de analizar el historial de movimientos para generar alertas de stock mínimo, detectar productos de baja rotación y sugerir cantidades de reposición que apoyen la toma de decisiones del administrador


---

## 1.2 Business Goals

Los principales objetivos de negocio son:

- Reducir pérdidas ocasionadas por desabastecimiento o exceso de inventario
- Centralizar la gestión de los movimientos de inventario
- Mejorar la trazabilidad de las operaciones realizadas sobre los productos
- Disminuir errores derivados de procesos manuales
- Facilitar la toma de decisiones mediante indicadores y recomendaciones automáticas
- Optimizar la planificación de compras utilizando información histórica del inventario


---

## 1.3 Main Functional Requirements (Inventory Movement Module)

### RF-09 Registrar entradas de inventario

El sistema deberá permitir registrar el ingreso de mercancía al inventario actualizando automáticamente el stock disponible

### RF-10 Registrar salidas de inventario

El sistema deberá registrar las salidas de productos manteniendo actualizado el inventario

### RF-11 Actualización automática del stock

Cada movimiento deberá modificar automáticamente las existencias disponibles

### RF-12 Consultar historial de movimientos

El usuario podrá consultar todas las entradas y salidas realizadas sobre un producto
