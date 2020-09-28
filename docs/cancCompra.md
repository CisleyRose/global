---
id: cancCompra
title: API Cancelacion Compra
sidebar_label: API Cancelacion Compra
---

## `Method GET` /getCancCompraList
**Obtiene el listado de cancelaciones de compras**

Obtiene el listado de las cancelaciones de compras realizadas en la empresa

**Example Output**


```
[
    {
        "cancCompraId": 1,
        "dateMod": "2020-09-28T00:00:00.000+00:00",
        "estado": "v",
        "fecha": "2020-09-28T00:00:00.000+00:00",
        "lantcanc": "0",
        "lanticipo": "0",
        "moneda": "us",
        "notas": "nota1",
        "proveedor": "global",
        "saldoant": "quinientos",
        "timeMod": "2020-09-28T00:00:00.000+00:00",
        "whoMod": "258741"
    },
    {
        "cancCompraId": 2,
        "dateMod": "2020-09-28T00:00:00.000+00:00",
        "estado": "v",
        "fecha": "2020-09-28T00:00:00.000+00:00",
        "lantcanc": "0",
        "lanticipo": "0",
        "moneda": "us",
        "notas": "nota2",
        "proveedor": "global",
        "saldoant": "trecientos",
        "timeMod": "2020-09-28T00:00:00.000+00:00",
        "whoMod": "258741"
    }
]
```

## `Method POST` /saveCancCompra
**Crea una cancelación de compra**

Crea la información de la Cancelación de compra indicada.

**Example Input**

```
	
     {
        "cancCompraId": null,
        "dateMod": "2020-09-28",
        "estado": "v",
        "fecha": "2020-09-28",
        "lantcanc": "0",
        "lanticipo": "0",
        "moneda": "us",
        "notas": "nota2",
        "proveedor": "global",
        "saldoant": "trecientos",
        "timeMod": "2020-09-28",
        "whoMod": "258741"
    }

```

**Example Output**

```
	{
		"cancCompraId": 6,
		"dateMod": "2020-09-28T00:00:00.000+00:00",
		"estado": "v",
		"fecha": "2020-09-28T00:00:00.000+00:00",
		"lantcanc": "0",
		"lanticipo": "0",
		"moneda": "us",
		"notas": "nota2",
		"proveedor": "global",
		"saldoant": "trecientos",
		"timeMod": "2020-09-28T00:00:00.000+00:00",
		"whoMod": "258741"
	}

```
## `Method DELETE` /deleteCancCompra/{idCancCompra}
**Elimina una cancelacion de compra**

Elimina la información de la cancelacion de compra indicada

**Example Output**

```
[200 OK]
```
