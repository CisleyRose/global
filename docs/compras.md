---
id: compras
title: API Compras
sidebar_label: API Compras
---

## `Method GET` /getComprasList
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

## `Method POST` /saveCompra
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
	{
		"comprasId": 2,
		"cambio": "cambio1",
		"cancelado": "0",
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

```
## `Method DELETE` /deleteCompra/{idCompra}
**Elimina una Compra**

Elimina la información de la Compra indicada

**Example Output**

```
[200 OK]
```
