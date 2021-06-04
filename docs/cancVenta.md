---
id: cancVenta
title: API Cancelacion Venta
sidebar_label: API Cancelacion Venta
---

## `Method GET` /cance-ventas
**Obtiene el listado de cancelaciones de ventas**

Obtiene el listado de las cancelaciones de ventas realizadas en la empresa

**Example Output**


```
[
    {
        "cancVentaId": 1,
        "cambio": 15478,
        "cancv": 1254,
        "cliente": "global",
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "lantcanc": 1,
        "lanticipo": 1,
        "moneda": "us",
        "notas": "sin notas",
        "pdolar": 1589,
        "ppedido": 15896,
        "saldoant": 1587,
        "timeMod": "1:42:00",
        "whoMod": "158"
    },
    {
        "cancVentaId": 2,
        "cambio": 15478,
        "cancv": 1254,
        "cliente": "yaru",
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "lantcanc": 1,
        "lanticipo": 1,
        "moneda": "us",
        "notas": "sin notas",
        "pdolar": 1589,
        "ppedido": 15896,
        "saldoant": 1587,
        "timeMod": "1:42:00",
        "whoMod": "158"
    },
    {
        "cancVentaId": 3,
        "cambio": 15478,
        "cancv": 1254,
        "cliente": "yaru",
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "lantcanc": 1,
        "lanticipo": 1,
        "moneda": "us",
        "notas": "sin notas",
        "pdolar": 1589,
        "ppedido": 15896,
        "saldoant": 1587,
        "timeMod": "1:42:00",
        "whoMod": "158"
    }
]
```

## `Method GET` /cance-ventas/{idCancVenta}
**Obtiene una cancelacion de venta especifica según el id indicado**

Obtiene una cancelacion de venta especifica según el id indicado

**Example Output**


```
	{
		"cancVentaId": 3,
		"cambio": 15478,
		"cancv": 1254,
		"cliente": "yaru",
		"dateMod": "2021-05-26T00:00:00.000+00:00",
		"estado": 1,
		"fecha": "2021-05-26T00:00:00.000+00:00",
		"lantcanc": 1,
		"lanticipo": 1,
		"moneda": "us",
		"notas": "sin notas",
		"pdolar": 1589,
		"ppedido": 15896,
		"saldoant": 1587,
		"timeMod": "1:42:00",
		"whoMod": "158"
	}
```

## `Method POST` /cance-ventas
**Crea una cancelación de venta**

Crea la información de la Cancelación de venta indicada.

**Example Input**

```
	
    {
		"cancVentaId": null,
		"cambio": 15478,
		"cancv": 1254,
		"cliente": "yaru",
		"dateMod": "2021-05-26",
		"estado": 1,
		"fecha": "2021-05-26",
		"lantcanc": 1,
		"lanticipo": 1,
		"moneda": "us",
		"notas": "sin notas",
		"pdolar": 1589,
		"ppedido": 15896,
		"saldoant": 1587,
		"timeMod": "1:42:00",
		"whoMod": "158"
	}

```

**Example Output**

```
[201 OK]

```
## `Method DELETE` /cance-ventas/{idCancVenta}
**Elimina una cancelacion de venta**

Elimina la información de la cancelacion de venta indicada

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
