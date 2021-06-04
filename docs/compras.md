---
id: compras
title: API Compras
sidebar_label: API Compras
---

## `Method GET` /compras
**Consulta el listado de Compras**

Obtiene el listado de Compras existentes en la empresa

**Example Output**


```
[
    {
        "comprasId": 1,
        "cambio": "cambio",
        "cancelado": "1",
        "compra": "disponible",
        "control": "control1",
        "controlFin": "fin1",
        "dateMod": "2020-09-15T00:00:00.000+00:00",
        "docasoc": "1",
        "estado": "E",
        "factura": "facturado",
        "fecha": "2020-09-15T00:00:00.000+00:00",
        "lislrret": "1",
        "livaret": "1",
        "moneda": "us",
        "montoretiv": "200",
        "nigvcs": "algo1",
        "noInventar": "1",
        "notas": "sin notas",
        "nsubTotal": "1263",
        "numCompret": "156329",
        "plazoPago": "tri",
        "pomite": "1",
        "proveedor": "varios",
        "rettodoimp": "1",
        "timeMod": "2020-09-15T00:00:00.000+00:00",
        "whoMod": "1584",
        "pdireccion": "miami",
        "pcontrol": "control1",
        "pplanilla": "planilla1"
    }
]
```

## `Method GET` /compras/{idCompra}
**Obtiene una compra especifica según el id indicado**

Obtiene una compra especifica según el id indicado

**Example Output**


```
	{
		"comprasId": 2,
		"cambio": 1254,
		"cancelado": 0,
		"compra": "compra 2",
		"control": 1,
		"controlFin": 1,
		"dateMod": "2021-05-27T00:00:00.000+00:00",
		"docasoc": 1,
		"estado": 1,
		"factura": "factura",
		"fecha": "2021-05-27T00:00:00.000+00:00",
		"lislrret": 1,
		"livaret": 1,
		"moneda": "us",
		"montoretiv": 250.36,
		"nigvcs": 12,
		"noInventar": 1,
		"notas": "sin notas",
		"nsubTotal": 1254,
		"numCompret": "compra",
		"plazoPago": 1,
		"pomite": 1,
		"proveedor": "global",
		"rettodoimp": 1,
		"timeMod": "2021-05-27T00:00:00.000+00:00",
		"whoMod": "1547",
		"pcontrol": "control",
		"pdireccion": "vzla",
		"pplanilla": "planilla compra"
	}
```

## `Method POST` /compras
**Crea o actualiza una Compra**

Crea o actualiza la información de la Compra indicada.

**Example Input**

```
	
    {
        "comprasId": null,
        "cambio": "cambio1",
        "cancelado": "0",
        "compra": "disponible",
        "control": "control1",
        "controlFin": "fin1",
        "dateMod": "2020-09-15",
        "docasoc": "1",
        "estado": "E",
        "factura": "facturado",
        "fecha": "2020-09-15",
        "lislrret": "1",
        "livaret": "1",
        "moneda": "us",
        "montoretiv": "200",
        "nigvcs": "algo1",
        "noInventar": "1",
        "notas": "sin notas",
        "nsubTotal": "1263",
        "numCompret": "156329",
        "plazoPago": "tri",
        "pomite": "1",
        "proveedor": "varios",
        "rettodoimp": "1",
        "timeMod": "2020-09-15",
        "whoMod": "1584",
        "pdireccion": "miami",
        "pcontrol": "control1",
        "pplanilla": "planilla1"
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /compras/{idCompra}
**Elimina una Compra**

Elimina la información de la Compra indicada

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
