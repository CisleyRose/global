---
id: devolucion
title: API Devolucion
sidebar_label: API Devolucion
---

## `Method GET` /getEncDevolList
**Obtiene el encabezado de devoluciones de compra y devoluciones de venta**

Obtiene la información del encabezado de devoluciones de compra y devoluciones de venta

**Example Output**


```
[
    {
        "encDevolId": 2,
        "cambio": 2,
        "compra": null,
        "dateMod": "2020-10-16T00:00:00.000+00:00",
        "devComp": 0,
        "docasoc": 1,
        "entrada": 1,
        "estado": 1,
        "factura": "venta",
        "fecha": "2020-10-16T00:00:00.000+00:00",
        "moneda": "us",
        "motivo": "venta",
        "proveedor": "global",
        "timeMod": "16102020",
        "whoMod": "15874",
        "tipo": "venta",
        "cancv": 1,
        "devVent": 1,
        "notadcv1": "notas",
        "notadcv2": "notas",
        "salida": 1
    },
    {
        "encDevolId": 3,
        "cambio": 1,
        "compra": "producto",
        "dateMod": "2020-10-16T00:00:00.000+00:00",
        "devComp": 12,
        "docasoc": 1,
        "entrada": 1,
        "estado": 1,
        "factura": "compra",
        "fecha": "2020-10-16T00:00:00.000+00:00",
        "moneda": "us",
        "motivo": "compra",
        "proveedor": "global",
        "timeMod": "16102020",
        "whoMod": "15982",
        "tipo": "compra",
        "cancv": 0,
        "devVent": 0,
        "notadcv1": null,
        "notadcv2": null,
        "salida": 0
    }
]
```

## `Method POST` /saveEncDevol
**Crea o actualiza la información del encabezado de devoluciones de compra y de devoluciones de venta**

Crea o actualiza la información del encabezado de devoluciones de compra y de devoluciones de venta especificado.

**Example Input**

```
	
    {
        "encDevolId": null,
        "cambio": 1,
        "compra": "producto",
        "dateMod": "2020-10-16",
        "devComp": 12,
        "docasoc": 1,
        "entrada": 1,
        "estado": 1,
        "factura": "compra",
        "fecha": "2020-10-16",
        "moneda": "us",
        "motivo": "compra",
        "proveedor": "global",
        "timeMod": "16102020",
        "whoMod": "15982",
        "tipo": "compra",
        "cancv": 0,
        "devVent": 0,
        "notadcv1": null,
        "notadcv2": null,
        "salida": 0
    }

```

**Example Output**

```
	{
		"encDevolId": 3,
		"cambio": 1,
		"compra": "producto",
		"dateMod": "2020-10-16T00:00:00.000+00:00",
		"devComp": 12,
		"docasoc": 1,
		"entrada": 1,
		"estado": 1,
		"factura": "compra",
		"fecha": "2020-10-16T00:00:00.000+00:00",
		"moneda": "us",
		"motivo": "compra",
		"proveedor": "global",
		"timeMod": "16102020",
		"whoMod": "15982",
		"tipo": "compra",
		"cancv": 0,
		"devVent": 0,
		"notadcv1": null,
		"notadcv2": null,
		"salida": 0
	}

```
## `Method DELETE` /deleteEncDevol/{idEncDevol}
**Elimina un registro del encabezado de devoluciones de compra y devoluciones de venta**

Elimina la información del encabezado de devoluciones de compra y devoluciones de venta especificado

**Example Output**

```
[200 OK]
```

## `Method GET` /getDetDevolList
**Obtiene el listado de detalles de las devoluciones de compra y de las devoluciones de venta**

Obtiene la información del detalle de las devoluciones de compra y de las devoluciones de venta

**Example Output**


```
[
    {
        "detDevolId": 2,
        "almacen": "ven",
        "cantidad": 2,
        "devComp": 0,
        "itemComp": 0,
        "otroCosto": 10.0,
        "precio": 10.0,
        "tipo": "venta",
        "devVent": 1,
        "itemVent": 2
    },
    {
        "detDevolId": 3,
        "almacen": "com",
        "cantidad": 1,
        "devComp": 1,
        "itemComp": 1,
        "otroCosto": 12.0,
        "precio": 12.0,
        "tipo": "compra",
        "devVent": 0,
        "itemVent": 0
    }
]
```

## `Method POST` /saveDetDevol
**Crea o actualiza la información del detalle de devoluciones de compra y de devoluciones de venta**

Crea o actualiza la información del Detalle de devoluciones de compra y de devoluciones de venta especificada.

**Example Input**

```
	
    {
        "detDevolId": null,
        "almacen": "com",
        "cantidad": 1,
        "devComp": 1,
        "itemComp": 1,
        "otroCosto": 12.0,
        "precio": 12.0,
        "tipo": "compra",
        "devVent": 0,
        "itemVent": 0
    }

```

**Example Output**

```
	{
		"detDevolId": 3,
		"almacen": "com",
		"cantidad": 1,
		"devComp": 1,
		"itemComp": 1,
		"otroCosto": 12.0,
		"precio": 12.0,
		"tipo": "compra",
		"devVent": 0,
		"itemVent": 0
	}

```
## `Method DELETE` /deleteDetDevol/{idDetDevol}
**Elimina un registro del detalle de devoluciones de compra y devoluciones de venta**

Elimina la información del detalle de devoluciones de compra y devoluciones de venta especificado

**Example Output**

```
[200 OK]
```
