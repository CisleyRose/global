---
id: entradaInv
title: API Entrada de Inventario
sidebar_label: API Entrada de Inventario
---

## `Method GET` /enc-inventarios
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
## `Method GET` /enc-inventarios/{idEncEntradaInv}
**Obtiene un encabezado de entrada del inventario según el id indicado**

Obtiene un encabezado de entrada del inventario según el id indicado

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

## `Method POST` /enc-inventarios
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
[201 OK]
```

## `Method DELETE` /enc-inventarios/{idEncEntradaInv}
**Elimina un registro del encabezado de entradas del inventario**

Elimina la información del encabezado de entradas del inventario especificado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```

## `Method GET` /det-inventarios
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

## `Method GET` /det-inventarios/{idDetEntradaInv}
**Obtiene el listado de detalles de entradas del inventario**

Obtiene la información del detalle de entradas del inventario

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

## `Method POST` /det-inventarios
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
[201 OK]
```

## `Method DELETE` /det-inventarios/{idDetEntradaInv}
**Elimina un registro del detalle de entradas del inventario**

Elimina la información del detalle de entradas del inventario especificado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
