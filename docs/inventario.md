---
id: inventario
title: API Inventario
sidebar_label: API Inventario
---

## `Method GET` /getInventarioList
**Consulta el listado en la tabla Inventario**

Obtiene la información existente en Inventario

**Example Output**


```
[
    {
        "inventarId": 3,
        "ajustado": "C",
        "almacen": "RPC",
        "articulo": "HIGIENE",
        "cantMax": "23",
        "cantMin": "12",
        "existencia": "12",
        "inventario": "12",
        "invFisico": "12",
        "invXAlm": "12"
    },
    {
        "inventarId": 4,
        "ajustado": "A",
        "almacen": "RPC",
        "articulo": "HIGIENE",
        "cantMax": "23",
        "cantMin": "12",
        "existencia": "12",
        "inventario": "12",
        "invFisico": "12",
        "invXAlm": "12"
    },
    {
        "inventarId": 5,
        "ajustado": "F",
        "almacen": "RPC",
        "articulo": "HIGIENE",
        "cantMax": "23",
        "cantMin": "12",
        "existencia": "12",
        "inventario": "12",
        "invFisico": "12",
        "invXAlm": "12"
    }
]

```

## `Method POST` /saveInventario
**Crea o actualiza la información en la tabla Inventario**

Crea o actualiza la información en la tabla Inventario.

**Example Input**

```	    
    {
        "inventarId": null,
        "ajustado": "F",
        "almacen": "RPC",
        "articulo": "HIGIENE",
        "cantMax": "23",
        "cantMin": "12",
        "existencia": "12",
        "inventario": "12",
        "invFisico": "12",
        "invXAlm": "12"
    }

```

**Example Output**

```
	{
    "inventarId": 5,
    "ajustado": "F",
    "almacen": "RPC",
    "articulo": "HIGIENE",
    "cantMax": "23",
    "cantMin": "12",
    "existencia": "12",
    "inventario": "12",
    "invFisico": "12",
    "invXAlm": "12"
}

```
## `Method DELETE` /deleteInventario/{idInventario}
**Elimina un registro de la tabla Inventario**

Elimina la información del registro indicado por su id

**Example Output**

```
[200 OK]
```
