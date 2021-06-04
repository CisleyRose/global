---
id: cancCompra
title: API Cancelacion Compra
sidebar_label: API Cancelacion Compra
---

## `Method GET` /cance-compras
**Obtiene el listado de cancelaciones de compras**

Obtiene el listado de las cancelaciones de compras realizadas en la empresa

**Example Output**


```
[
    {
        "cancCompraId": 1,
        "cambio": 15478,
        "cancc": 1254,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "lantcanc": 1,
        "lanticipo": 1,
        "moneda": "us",
        "notas": "sin notas",
        "proveedor": "global",
        "saldoant": 152.266,
        "timeMod": "1:42:00",
        "whoMod": "1547"
    },
    {
        "cancCompraId": 2,
        "cambio": 15478,
        "cancc": 1254,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "lantcanc": 1,
        "lanticipo": 1,
        "moneda": "us",
        "notas": "sin notas",
        "proveedor": "yaru",
        "saldoant": 152.266,
        "timeMod": "1:42:00",
        "whoMod": "1547"
    },
    {
        "cancCompraId": 3,
        "cambio": 15478,
        "cancc": 1254,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "lantcanc": 1,
        "lanticipo": 1,
        "moneda": "us",
        "notas": "sin notas",
        "proveedor": "global2",
        "saldoant": 152.266,
        "timeMod": "1:42:00",
        "whoMod": "1547"
    }
]
```

## `Method GET` /cance-compras/{idCancCompra}
**Obtiene una cancelacion de compra especifica según el id indicado**

Obtiene una cancelacion de compra especifica según el id indicado

**Example Output**


```
	{
		"cancCompraId": 3,
		"cambio": 15478,
		"cancc": 1254,
		"dateMod": "2021-05-26T00:00:00.000+00:00",
		"estado": 1,
		"fecha": "2021-05-26T00:00:00.000+00:00",
		"lantcanc": 1,
		"lanticipo": 1,
		"moneda": "us",
		"notas": "sin notas",
		"proveedor": "global2",
		"saldoant": 152.266,
		"timeMod": "1:42:00",
		"whoMod": "1547"
	}
```

## `Method POST` /cance-compras
**Crea una cancelación de compra**

Crea la información de la Cancelación de compra indicada.

**Example Input**

```
	
    {
		"cancCompraId": null,
		"cambio": 15478,
		"cancc": 1254,
		"dateMod": "2021-06-03",
		"estado": 1,
		"fecha": "2021-06-03",
		"lantcanc": 1,
		"lanticipo": 1,
		"moneda": "us",
		"notas": "sin notas",
		"proveedor": "global2",
		"saldoant": 152.266,
		"timeMod": "1:42:00",
		"whoMod": "1547"
	}

```

**Example Output**

```
[201 OK]

```
## `Method DELETE` /cance-compras/{idCancCompra}
**Elimina una cancelacion de compra**

Elimina la información de la cancelacion de compra indicada

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
