---
id: entradaInv
title: API Entrada de Inventario
sidebar_label: API Entrada de Inventario
---

## `Method GET` /getEncEntradaInvList
**Obtiene el encabezado de entradas del inventario**

Obtiene la información del encabezado de entradas del inventario

**Example Output**


```
[
    {
        "encEntradaInvId": 2,
        "cambio": 1,
        "cliente": "global",
        "consignado": 1,
        "dateMod": "2020-11-20T00:00:00.000+00:00",
        "entrada": 1,
        "estado": 1,
        "factcompra": "compra",
        "facturable": 1,
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "moneda": "us",
        "motivo": "compra",
        "origen": 1,
        "provcompra": "prov",
        "provorig": "prov",
        "timeMod": "2:45:00",
        "whoMod": "12587"
    },
    {
        "encEntradaInvId": 3,
        "cambio": 1,
        "cliente": "global",
        "consignado": 1,
        "dateMod": "2020-11-20T00:00:00.000+00:00",
        "entrada": 1,
        "estado": 1,
        "factcompra": "compra",
        "facturable": 1,
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "moneda": "us",
        "motivo": "compra",
        "origen": 1,
        "provcompra": "prov",
        "provorig": "prov",
        "timeMod": "2:45:00",
        "whoMod": "12587"
    }
]
```

## `Method POST` /saveEncEntradaInv
**Crea o actualiza la información del encabezado de entradas del inventario**

Crea o actualiza la información del encabezado de entradas del inventario.

**Example Input**

```
	
    {
        "encEntradaInvId": null,
        "cambio": 1,
        "cliente": "global",
        "consignado": 1,
        "dateMod": "2020-11-20",
        "entrada": 1,
        "estado": 1,
        "factcompra": "compra",
        "facturable": 1,
        "fecha": "2020-11-20",
        "moneda": "us",
        "motivo": "compra",
        "origen": 1,
        "provcompra": "prov",
        "provorig": "prov",
        "timeMod": "2:45:00",
        "whoMod": "12587"
    }

```

**Example Output**

```
	{
		"encEntradaInvId": 3,
		"cambio": 1,
		"cliente": "global",
		"consignado": 1,
		"dateMod": "2020-11-20T00:00:00.000+00:00",
		"entrada": 1,
		"estado": 1,
		"factcompra": "compra",
		"facturable": 1,
		"fecha": "2020-11-20T00:00:00.000+00:00",
		"moneda": "us",
		"motivo": "compra",
		"origen": 1,
		"provcompra": "prov",
		"provorig": "prov",
		"timeMod": "2:45:00",
		"whoMod": "12587"
	}

```
## `Method DELETE` /deleteEncEntradaInv/{idEncEntradaInv}
**Elimina un registro del encabezado de entradas del inventario**

Elimina la información del encabezado de entradas del inventario especificado

**Example Output**

```
[200 OK]
```

## `Method GET` /getDetEntradaInvList
**Obtiene el listado de detalles de entradas del inventario**

Obtiene la información del detalle de entradas del inventario

**Example Output**


```
[
    {
        "detEntradaInvId": 2,
        "almacen": "alm",
        "articulo": "camisa",
        "cantidad": 1,
        "consumo": "camisas",
        "devuelto": 120,
        "docasoc": "documento",
        "entrada": 1,
        "fechavenc": "2020-11-20T00:00:00.000+00:00",
        "igvcs": 1,
        "item": 1,
        "itemdoc": 1,
        "lote": "lote1",
        "otrocosto": 200,
        "precio": 200,
        "recibido": null
    },
    {
        "detEntradaInvId": 3,
        "almacen": "alm",
        "articulo": "camisa",
        "cantidad": 1,
        "consumo": "camisas",
        "devuelto": 120,
        "docasoc": "documento",
        "entrada": 1,
        "fechavenc": "2020-11-20T00:00:00.000+00:00",
        "igvcs": 1,
        "item": 1,
        "itemdoc": 1,
        "lote": "lote1",
        "otrocosto": 200,
        "precio": 200,
        "recibido": null
    }
]

```

## `Method POST` /saveDetEntradaInv
**Crea o actualiza la información del detalle de entradas del inventario**

Crea o actualiza la información del detalle de entradas del inventario.

**Example Input**

```
	
    {
        "detEntradaInvId": null,
        "almacen": "alm",
        "articulo": "camisa",
        "cantidad": 1,
        "consumo": "camisas",
        "devuelto": 120,
        "docasoc": "documento",
        "entrada": 1,
        "fechavenc": "2020-11-20",
        "igvcs": 1,
        "item": 1,
        "itemdoc": 1,
        "lote": "lote1",
        "otrocosto": 200,
        "precio": 200,
        "recibido": null
    }

```

**Example Output**

```
	{
		"detEntradaInvId": 3,
		"almacen": "alm",
		"articulo": "camisa",
		"cantidad": 1,
		"consumo": "camisas",
		"devuelto": 120,
		"docasoc": "documento",
		"entrada": 1,
		"fechavenc": "2020-11-20T00:00:00.000+00:00",
		"igvcs": 1,
		"item": 1,
		"itemdoc": 1,
		"lote": "lote1",
		"otrocosto": 200,
		"precio": 200,
		"recibido": null
	}

```
## `Method DELETE` /deleteDetEntradaInv/{idDetEntradaInv}
**Elimina un registro del detalle de entradas del inventario**

Elimina la información del detalle de entradas del inventario especificado

**Example Output**

```
[200 OK]
```
