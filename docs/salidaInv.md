---
id: salidaInv
title: API Salida de Inventario
sidebar_label: API Salida de Inventario
---

## `Method GET` /enc-salida-inventarios
**Obtiene el encabezado de salidas del inventario**

Obtiene la información del encabezado de salidas del inventario

**Example Output**


```
[
    {
        "encSalidaInvId": 2,
        "almacen": "alm",
        "cambio": 1,
        "cliente": "global",
        "consignado": 1,
        "dateMod": "2020-11-20T00:00:00.000+00:00",
        "destino": 1,
        "entrada": 0,
        "estado": 1,
        "facturable": 1,
        "factventa": "venta",
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "moneda": "us",
        "motivo": "venta",
        "pauto": 1,
        "pformap": "fo",
        "pmonto": 200.0,
        "pnumero": 1,
        "pretiro": 200,
        "proveedor": "global",
        "requisicio": 1,
        "salida": 1,
        "timeMod": "2:48:00",
        "whoMod": "12584"
    },
    {
        "encSalidaInvId": 3,
        "almacen": "alm",
        "cambio": 1,
        "cliente": "global",
        "consignado": 1,
        "dateMod": "2020-11-20T00:00:00.000+00:00",
        "destino": 1,
        "entrada": 0,
        "estado": 1,
        "facturable": 1,
        "factventa": "venta",
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "moneda": "us",
        "motivo": "venta",
        "pauto": 1,
        "pformap": "fo",
        "pmonto": 200.0,
        "pnumero": 1,
        "pretiro": 200,
        "proveedor": "global",
        "requisicio": 1,
        "salida": 1,
        "timeMod": "2:48:00",
        "whoMod": "12584"
    }
]
```

## `Method GET` /enc-salida-inventarios/{idEncSalidaInv}
**Obtiene un encabezado de salidas del inventario según el id indicado**

Obtiene un encabezado de salidas del inventario según el id indicado

**Example Output**


```
    {
        "encSalidaInvId": 3,
        "almacen": "alm",
        "cambio": 1,
        "cliente": "global",
        "consignado": 1,
        "dateMod": "2020-11-20T00:00:00.000+00:00",
        "destino": 1,
        "entrada": 0,
        "estado": 1,
        "facturable": 1,
        "factventa": "venta",
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "moneda": "us",
        "motivo": "venta",
        "pauto": 1,
        "pformap": "fo",
        "pmonto": 200.0,
        "pnumero": 1,
        "pretiro": 200,
        "proveedor": "global",
        "requisicio": 1,
        "salida": 1,
        "timeMod": "2:48:00",
        "whoMod": "12584"
    }

```


## `Method POST` /enc-salida-inventarios
**Crea o actualiza la información del encabezado de salidas del inventario**

Crea o actualiza la información del encabezado de salidas del inventario.

**Example Input**

```
	
   {
        "encSalidaInvId": null,
        "almacen": "alm",
        "cambio": 1,
        "cliente": "global",
        "consignado": 1,
        "dateMod": "2020-11-20",
        "destino": 1,
        "entrada": 0,
        "estado": 1,
        "facturable": 1,
        "factventa": "venta",
        "fecha": "2020-11-20",
        "moneda": "us",
        "motivo": "venta",
        "pauto": 1,
        "pformap": "fo",
        "pmonto": 200.0,
        "pnumero": 1,
        "pretiro": 200,
        "proveedor": "global",
        "requisicio": 1,
        "salida": 1,
        "timeMod": "2:48:00",
        "whoMod": "12584"
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /enc-salida-inventarios/{idEncSalidaInv}
**Elimina un registro del encabezado de salidas del inventario**

Elimina la información del encabezado de salidas del inventario especificado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```

## `Method GET` /det-salida-inventarios
**Obtiene el listado de detalles de salidas del inventario**

Obtiene la información del detalle de salidas del inventario

**Example Output**


```
[
    {
        "detSalidaInvId": 2,
        "almacen": "alm",
        "articulo": "camisa",
        "cantidad": 1,
        "costo": 200,
        "descmonto": 0,
        "descripcio": "camisa",
        "descuento": 0,
        "devuelto": 0,
        "docasoc": "documento",
        "entregado": 1,
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "igvcs": 1,
        "item": 1,
        "itemdoc": 1,
        "numprecio": 1,
        "precio": 200,
        "salida": 1
    },
    {
        "detSalidaInvId": 3,
        "almacen": "alm",
        "articulo": "camisa",
        "cantidad": 1,
        "costo": 200,
        "descmonto": 0,
        "descripcio": "camisa",
        "descuento": 0,
        "devuelto": 0,
        "docasoc": "documento",
        "entregado": 1,
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "igvcs": 1,
        "item": 1,
        "itemdoc": 1,
        "numprecio": 1,
        "precio": 200,
        "salida": 1
    }
]

```

## `Method GET` /det-salida-inventarios/{idDetSalidaInv}
**Obtiene un detalle de salidas del inventario según el id indicado**

Obtiene un detalle de salidas del inventario según el id indicado

**Example Output**


```
    {
        "detSalidaInvId": 3,
        "almacen": "alm",
        "articulo": "camisa",
        "cantidad": 1,
        "costo": 200,
        "descmonto": 0,
        "descripcio": "camisa",
        "descuento": 0,
        "devuelto": 0,
        "docasoc": "documento",
        "entregado": 1,
        "fecha": "2020-11-20T00:00:00.000+00:00",
        "igvcs": 1,
        "item": 1,
        "itemdoc": 1,
        "numprecio": 1,
        "precio": 200,
        "salida": 1
    }
	
```


## `Method POST` /det-salida-inventarios
**Crea o actualiza la información del detalle de salidas del inventario**

Crea o actualiza la información del detalle de salidas del inventario.

**Example Input**

```
	
    {
        "detSalidaInvId": null,
        "almacen": "alm",
        "articulo": "camisa",
        "cantidad": 1,
        "costo": 200,
        "descmonto": 0,
        "descripcio": "camisa",
        "descuento": 0,
        "devuelto": 0,
        "docasoc": "documento",
        "entregado": 1,
        "fecha": "2020-11-20",
        "igvcs": 1,
        "item": 1,
        "itemdoc": 1,
        "numprecio": 1,
        "precio": 200,
        "salida": 1
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /det-salida-inventarios/{idDetSalidaInv}
**Elimina un registro del detalle de salidas del inventario**

Elimina la información del detalle de salidas del inventario especificado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
