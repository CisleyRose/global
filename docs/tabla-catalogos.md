---
id: tabla-catalogos
title: Contenido de las tablas Catálogo
sidebar_label: Tablas Catalogo
---


## Encabezado de Catálogo

**Nombre de la tabla:** ENCCATALOGO

**Descripción:** Tabla que contendrá todos los encabezados de los catálogos del sistema global


| Campo             | Tamaño   | Tipo de dato      | Descripción                                                |        
| ----------------- | -------- | ----------------- | ---------------------------------------------------------- |
| `encCatalogoId`   | 10       | Long              | Id genérico. Se asigna de manera automática por el sistema | 
| `code`            | 2        | Long              | Número de código del encabezado del catálogo               |     
| `dateMod`         | 19       | Date              | Fecha en la que se modifica el registro                    |     
| `descriptio`      | 25       | Character varying | Nombre del encabezado del catálogo                         |     
| `timeMod`         | 8        | Character varying | Hora en la que se modifica el registro                     |    
| `whoMod`          | 10       | Character varying | Usuario que modifica que registro                          | 


## Detalle de Catálogo

**Nombre de la tabla:** DETCATALOGO

**Descripción:** Tabla que contendrá todos los detalles de los catálogos del sistema global. Cada detalle de catálogo se encuentra asignado a un código de encabezado de catálogo


| Campo             | Tamaño   | Tipo de dato      | Descripción                                                   |        
| ----------------- | -------- | ----------------- | ------------------------------------------------------------- |
| `detCatalogoId`   | 10       | Long              | Id genérico. Se asigna de manera automática por el sistema    | 
| `codeDet`         | 10       | Long              | Número de código del detalle del catálogo                     |     
| `dateMod`         | 19       | Date              | Fecha en la que se modifica el registro                       |     
| `description`     | 255      | Character varying | Nombre del detalle del catálogo                               | 
| `comision`        | 255      | Integer           | Monto que se descuenta al realizar una operación              |
| `valorMoneda`     | 255      | Long              | Coversión del monto en moneda extranjera a monto en bolívares |
| `modoPago`        | 255      | Character varying | Indicador del impuesto que se debe aplicar a la operación     |
| `percentage`      | 255      | Character varying | Porcentaje del impuesto                                       |    
| `timeMod`         | 8        | Character varying | Hora en la que se modifica el registro                        |    
| `whoMod`          | 10       | Character varying | Usuario que modifica que registro                             |

**Relaciones:** ENCCATALOGO **Campos clave:** code











