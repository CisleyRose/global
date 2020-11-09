---
id: pedido
title: API Pedidos
sidebar_label: API Pedidos
---

## `Method GET` /getEncPedidoList
**Obtiene el encabezado de pedidos**

Obtiene la información del encabezado de pedidos

**Example Output**


```
[
    {
        "encPedidoId": 2,
        "cambio": 13,
        "cliente": "global",
        "dateMod": "2020-11-09T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2020-11-09T00:00:00.000+00:00",
        "moneda": "us",
        "notas": "sin notas",
        "pedidos": 1,
        "timeMod": "2:29:00",
        "whoMod": "12365"
    },
    {
        "encPedidoId": 3,
        "cambio": 14,
        "cliente": "global",
        "dateMod": "2020-11-09T00:00:00.000+00:00",
        "estado": 1,
        "fecha": "2020-11-09T00:00:00.000+00:00",
        "moneda": "us",
        "notas": "sin notas",
        "pedidos": 1,
        "timeMod": "2:29:00",
        "whoMod": "12365"
    }
]
```

## `Method POST` /saveEncPedido
**Crea o actualiza la información del encabezado de pedidos**

Crea o actualiza la información del encabezado de pedidos especificado.

**Example Input**

```
	
    {
        "encPedidoId": null,
        "cambio": 14,
        "cliente": "global",
        "dateMod": "2020-11-09",
        "estado": 1,
        "fecha": "2020-11-09",
        "moneda": "us",
        "notas": "sin notas",
        "pedidos": 1,
        "timeMod": "2:29:00",
        "whoMod": "12365"
    }

```

**Example Output**

```
	{
		"encPedidoId": 3,
		"cambio": 14,
		"cliente": "global",
		"dateMod": "2020-11-09T00:00:00.000+00:00",
		"estado": 1,
		"fecha": "2020-11-09T00:00:00.000+00:00",
		"moneda": "us",
		"notas": "sin notas",
		"pedidos": 1,
		"timeMod": "2:29:00",
		"whoMod": "12365"
	}

```
## `Method DELETE` /deleteEncPedido/{idEncPedido}
**Elimina un registro del encabezado de los pedidos**

Elimina la información del encabezado de  pedidos especificado

**Example Output**

```
[200 OK]
```

## `Method GET` /getDetPedidoList
**Obtiene el listado de detalles de pedidos**

Obtiene la información del detalle de pedidos

**Example Output**


```
[
    {
        "detPedidoId": 2,
        "articulo": "camisa",
        "cantidad": 1,
        "descMonto": 12,
        "descripcio": "camisa",
        "descuento": 0,
        "facturado": 1,
        "igvcs": 1,
        "item": 1,
        "itemDoc": "camisa",
        "numPrecio": 120,
        "pedido": 1,
        "precio": 120,
        "urgencia": 1
    },
    {
        "detPedidoId": 3,
        "articulo": "camisa",
        "cantidad": 1,
        "descMonto": 12,
        "descripcio": "camisa",
        "descuento": 0,
        "facturado": 1,
        "igvcs": 1,
        "item": 1,
        "itemDoc": "camisa",
        "numPrecio": 120,
        "pedido": 1,
        "precio": 120,
        "urgencia": 1
    }
]
```

## `Method POST` /saveDetPedido
**Crea o actualiza la información del detalle de pedidos**

Crea o actualiza la información del detalle de pedidos especificado.

**Example Input**

```
	
    {
        "detPedidoId": null,
        "articulo": "camisa",
        "cantidad": 1,
        "descMonto": 12,
        "descripcio": "camisa",
        "descuento": 0,
        "facturado": 1,
        "igvcs": 1,
        "item": 1,
        "itemDoc": "camisa",
        "numPrecio": 120,
        "pedido": 1,
        "precio": 120,
        "urgencia": 1
    }

```

**Example Output**

```
	{
		"detPedidoId": 3,
		"articulo": "camisa",
		"cantidad": 1,
		"descMonto": 12,
		"descripcio": "camisa",
		"descuento": 0,
		"facturado": 1,
		"igvcs": 1,
		"item": 1,
		"itemDoc": "camisa",
		"numPrecio": 120,
		"pedido": 1,
		"precio": 120,
		"urgencia": 1
	}

```
## `Method DELETE` /deleteDetPedido/{idDetPedido}
**Elimina un registro del detalle de los pedidos**

Elimina la información del detalle del pedido especificado

**Example Output**

```
[200 OK]
```
