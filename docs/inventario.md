---
id: inventario
title: API Inventario
sidebar_label: API Inventario
---

## `Method GET` /inventarios
**Consulta el listado en la tabla Inventario**

Obtiene la información existente en Inventario

**Example Output**


```
[
    {
        "inventarId": 1,
        "ajustado": 1,
        "almacen": "alm",
        "articulo": "jabon",
        "cantMax": 159,
        "cantMin": 1,
        "stock": 100,
        "cantidad": 100,
        "inventario": "Inventario 1\n",
        "invFisico": 1,
        "invXAlm": "1"
    },
    {
        "inventarId": 2,
        "ajustado": 1,
        "almacen": "alm",
        "articulo": "shampoo",
        "cantMax": 159,
        "cantMin": 1,
        "stock": 100,
        "cantidad": 100,
        "inventario": "Inventario 1",
        "invFisico": 1,
        "invXAlm": "1"
    },
    {
        "inventarId": 3,
        "ajustado": 1,
        "almacen": "alm",
        "articulo": "acondicionador",
        "cantMax": 159,
        "cantMin": 1,
        "stock": 100,
        "cantidad": 100,
        "inventario": "Inventario 1",
        "invFisico": 1,
        "invXAlm": "1"
    }
]
```

## `Method GET` /inventarios/{idInventario}
**Obtiene un inventario especifico según el id indicado**

Obtiene un inventario especifico según el id indicado

**Example Output**


```
	{
		"inventarId": 2,
		"ajustado": 1,
		"almacen": "alm",
		"articulo": "shampoo",
		"cantMax": 159,
		"cantMin": 1,
		"stock": 100,
		"cantidad": 100,
		"inventario": "Inventario 1",
		"invFisico": 1,
		"invXAlm": "1"
	}
```

## `Method POST` /inventarios
**Crea o actualiza la información en la tabla Inventario**

Crea o actualiza la información en la tabla Inventario.

**Example Input**

```	    
    {
		"inventarId": null,
		"ajustado": 1,
		"almacen": "alm",
		"articulo": "acondicionar",
		"cantMax": 159,
		"cantMin": 1,
		"stock": 100,
		"cantidad": 100,
		"inventario": "Inventario 1",
		"invFisico": 1,
		"invXAlm": "1"
	}

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /inventarios/{idInventario}
**Elimina un registro de la tabla Inventario**

Elimina la información del registro indicado por su id

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
