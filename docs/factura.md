---
id: factura
title: API Factura
sidebar_label: API Factura
---

## `Method GET` /enc-facturas
**Obtiene el encabezado de datos de la pantalla de factura**

Obtiene la información del encabezado de datos de la pantalla de factura

**Example Output**


```
[
    {
        "datosFactuId": 1,
        "caja": "c1",
        "cajero": "c2",
        "cambio": 1235,
        "cliente": "global",
        "control": 123,
        "controlFin": 123,
        "dateMod": "2020-10-27T00:00:00.000+00:00",
        "efectivo": 1235,
        "estado": 2,
        "factura": "factura1",
        "fecha": "2020-10-27T00:00:00.000+00:00",
        "lexis": 15,
        "nigvcs": 58,
        "notas": "sin notas",
        "plazoPago": 12,
        "plinea1": "qw",
        "plinea2": "15",
        "timeMod": "10:30:00",
        "ultfact": "factura1",
        "vendedor": "gb",
        "whoMod": "1587",
        "nsubTotal": 1254
    },
    {
        "datosFactuId": 2,
        "caja": "c1",
        "cajero": "c2",
        "cambio": 1235,
        "cliente": "global",
        "control": 123,
        "controlFin": 123,
        "dateMod": "2020-10-27T00:00:00.000+00:00",
        "efectivo": 1235,
        "estado": 2,
        "factura": "factura1",
        "fecha": "2020-10-27T00:00:00.000+00:00",
        "lexis": 15,
        "nigvcs": 58,
        "notas": "sin notas",
        "plazoPago": 12,
        "plinea1": "qw",
        "plinea2": "15",
        "timeMod": "10:30:00",
        "ultfact": "factura1",
        "vendedor": "gb",
        "whoMod": "1587",
        "nsubTotal": 1254
    }
]
```

## `Method GET` /enc-facturas/{idDatFact}
**Obtiene un encabezado de datos de la pantalla de factura según el id indicado**

Obtiene un encabezado de datos de la pantalla de factura según el id indicado

**Example Output**


```

    {
        "datosFactuId": 2,
        "caja": "c1",
        "cajero": "c2",
        "cambio": 1235,
        "cliente": "global",
        "control": 123,
        "controlFin": 123,
        "dateMod": "2020-10-27T00:00:00.000+00:00",
        "efectivo": 1235,
        "estado": 2,
        "factura": "factura1",
        "fecha": "2020-10-27T00:00:00.000+00:00",
        "lexis": 15,
        "nigvcs": 58,
        "notas": "sin notas",
        "plazoPago": 12,
        "plinea1": "qw",
        "plinea2": "15",
        "timeMod": "10:30:00",
        "ultfact": "factura1",
        "vendedor": "gb",
        "whoMod": "1587",
        "nsubTotal": 1254
    }

```


## `Method POST` /enc-facturas
**Crea o actualiza la información del encabezado de datos de la pantalla de factura**

Crea o actualiza la información del encabezado de datos de la pantalla de factura especificado.

**Example Input**

```
	
    {
        "datosFactuId": null,
        "caja": "c1",
        "cajero": "c2",
        "cambio": 1235,
        "cliente": "global",
        "control": 123,
        "controlFin": 123,
        "dateMod": "2020-10-27T00:00:00.000+00:00",
        "efectivo": 1235,
        "estado": 2,
        "factura": "factura1",
        "fecha": "2020-10-27T00:00:00.000+00:00",
        "lexis": 15,
        "nigvcs": 58,
        "notas": "sin notas",
        "plazoPago": 12,
        "plinea1": "qw",
        "plinea2": "15",
        "timeMod": "10:30:00",
        "ultfact": "factura1",
        "vendedor": "gb",
        "whoMod": "1587",
        "nsubTotal": 1254
    }

```

**Example Output**

```
[201 OK]

```
## `Method DELETE` /enc-facturas/{idDatFact}
**Elimina un registro del encabezado de datos de la pantalla de factura**

Elimina la información del encabezado de datos de la pantalla de factura

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```

## `Method GET` /det-facturas
**Obtiene el listado de detalles de la pantalla factura y detalles de pago de factura**

Obtiene la información de detalles de la pantalla factura y detalles de pago de factura

**Example Output**


```
[
    
    {
        "detPagoFactuId": 1,
        "almacen": "alm",
        "articulo": "computadora",
        "cantidad": 1,
        "costo": 750.0,
        "descMonto": 200.0,
        "descripcio": "compu",
        "descuento": 10.0,
        "factura": "factura1",
        "igvcs": 12,
        "item": 1,
        "numPrecio": 12,
        "precio": 750.0,
        "tipoDetalle": "pantalla",
        "cuenta": 0,
        "fechaDoc": null,
        "formaPago": null,
        "monto": 0.0,
        "numDoc": null,
        "origenDoc": null
    },
    {
        "detPagoFactuId": 2,
        "almacen": null,
        "articulo": null,
        "cantidad": 0,
        "costo": 0.0,
        "descMonto": 0.0,
        "descripcio": "compu",
        "descuento": 0.0,
        "factura": "factura1",
        "igvcs": 0,
        "item": 0,
        "numPrecio": 0,
        "precio": 0.0,
        "tipoDetalle": "detalle pago",
        "cuenta": 12,
        "fechaDoc": "2020-10-27T00:00:00.000+00:00",
        "formaPago": "db",
        "monto": 750.0,
        "numDoc": "12",
        "origenDoc": "12"
    }
]

```

## `Method GET` /det-facturas/{idDetFact}
**Obtiene un detalle de la pantalla factura y detalle de pago de factura según el id indicado**

Obtiene un detalle de la pantalla factura y detalle de pago de factura

**Example Output**


```
    {
        "detPagoFactuId": 2,
        "almacen": null,
        "articulo": null,
        "cantidad": 0,
        "costo": 0.0,
        "descMonto": 0.0,
        "descripcio": "compu",
        "descuento": 0.0,
        "factura": "factura1",
        "igvcs": 0,
        "item": 0,
        "numPrecio": 0,
        "precio": 0.0,
        "tipoDetalle": "detalle pago",
        "cuenta": 12,
        "fechaDoc": "2020-10-27T00:00:00.000+00:00",
        "formaPago": "db",
        "monto": 750.0,
        "numDoc": "12",
        "origenDoc": "12"
    }

```


## `Method POST` /det-facturas
**Crea o actualiza la información del detalle de la pantalla factura y detalle de pago de factura**

Crea o actualiza la información del Detalle de la pantalla factura y detalle de pago de factura especificada.

**Example Input**

```
	
    {
        "detPagoFactuId": null,
        "almacen": null,
        "articulo": null,
        "cantidad": 0,
        "costo": 0.0,
        "descMonto": 0.0,
        "descripcio": "compu",
        "descuento": 0.0,
        "factura": "factura1",
        "igvcs": 0,
        "item": 0,
        "numPrecio": 0,
        "precio": 0.0,
        "tipoDetalle": "detalle pago",
        "cuenta": 12,
        "fechaDoc": "2020-10-27T00:00:00.000+00:00",
        "formaPago": "db",
        "monto": 750.0,
        "numDoc": "12",
        "origenDoc": "12"
    }

```

**Example Output**

```
[201 OK]
```
## `Method DELETE` /det-facturas/{idDetFact}
**Elimina un registro del detalle de la pantalla factura y detalle de pago de factura**

Elimina la información del detalle de la pantalla factura y detalle de pago de factura especificado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
