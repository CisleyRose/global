---
id: cancVenta
title: API Cancelacion Venta
sidebar_label: API Cancelacion Venta
---

## `Method GET` /getCancVentaList
**Obtiene el listado de cancelaciones de ventas**

Obtiene el listado de las cancelaciones de ventas realizadas en la empresa

**Example Output**


```
[
    {
        "cancVentaId": 1,
        "cancv": "159632",
        "cliente": "global",
        "dateMod": "2020-09-28T00:00:00.000+00:00",
        "estado": "v",
        "fecha": "2020-09-28T00:00:00.000+00:00",
        "lantcanc": "1",
        "lanticipo": "1",
        "moneda": "us",
        "notas": "nota1",
        "pdolar": "14587",
        "ppedido": "pedido1",
        "saldoant": "159632",
        "timeMod": "2020-09-28T00:00:00.000+00:00",
        "whoMod": "158742"
    },
    {
        "cancVentaId": 2,
        "cancv": "159632",
        "cliente": "global",
        "dateMod": "2020-09-28T00:00:00.000+00:00",
        "estado": "v",
        "fecha": "2020-09-28T00:00:00.000+00:00",
        "lantcanc": "1",
        "lanticipo": "1",
        "moneda": "us",
        "notas": "nota1",
        "pdolar": "14587",
        "ppedido": "pedido1",
        "saldoant": "159632",
        "timeMod": "2020-09-28T00:00:00.000+00:00",
        "whoMod": "158742"
    },
    {
        "cancVentaId": 3,
        "cancv": "159632",
        "cliente": "global",
        "dateMod": "2020-09-28T00:00:00.000+00:00",
        "estado": "v",
        "fecha": "2020-09-28T00:00:00.000+00:00",
        "lantcanc": "1",
        "lanticipo": "1",
        "moneda": "us",
        "notas": "nota1",
        "pdolar": "14587",
        "ppedido": "pedido1",
        "saldoant": "159632",
        "timeMod": "2020-09-28T00:00:00.000+00:00",
        "whoMod": "158742"
    }
]
```

## `Method POST` /saveCancVenta
**Crea una cancelación de venta**

Crea la información de la Cancelación de venta indicada.

**Example Input**

```
	
     {
        "cancVentaId": null,
        "cancv": "159632",
        "cliente": "global",
        "dateMod": "2020-09-28",
        "estado": "v",
        "fecha": "2020-09-28",
        "lantcanc": "1",
        "lanticipo": "1",
        "moneda": "us",
        "notas": "nota1",
        "pdolar": "14587",
        "ppedido": "pedido1",
        "saldoant": "159632",
        "timeMod": "2020-09-28",
        "whoMod": "158742"
    }

```

**Example Output**

```
	{
		"cancVentaId": 6,
		"cancv": "159632",
		"cliente": "global",
		"dateMod": "2020-09-28T00:00:00.000+00:00",
		"estado": "v",
		"fecha": "2020-09-28T00:00:00.000+00:00",
		"lantcanc": "1",
		"lanticipo": "1",
		"moneda": "us",
		"notas": "nota1",
		"pdolar": "14587",
		"ppedido": "pedido1",
		"saldoant": "159632",
		"timeMod": "2020-09-28T00:00:00.000+00:00",
		"whoMod": "158742"
	}

```
## `Method DELETE` /deleteCancVenta/{idCancVenta}
**Elimina una cancelacion de venta**

Elimina la información de la cancelacion de venta indicada

**Example Output**

```
[200 OK]
```
