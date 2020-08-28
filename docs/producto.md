---
id: producto
title: API Productos
sidebar_label: API Productos
---

## `Method GET` /getProductos
**Consulta el listado de productos**

Obtiene el listado de productos existentes

**Example Output**


```
[
    {
        "productId": 2,
        "almacen": "RPD",
        "area": "RP",
        "articulo": "HIGIENE",
        "categoria": "HOGAR",
        "codBarra": "12123456878",
        "codRet": null,
        "costo": "200",
        "costoProm": "190",
        "cuenta1": "12365478952",
        "cuenta2": null,
        "cuenta3": null,
        "cuenta4": null,
        "cuenta5": null,
        "grupo": "HOGAR",
        "descPvp": "prom",
        "descPvp2": null,
        "descPvp3": null,
        "descPvp4": null,
        "descPvp5": null,
        "factVenta": "1256",
        "factVenta2": null,
        "factVenta3": null,
        "factVenta4": null,
        "factVenta5": null,
        "forma": "HG",
        "igvcs": null,
        "marca": "PUREZA",
        "medida": null,
        "modelo": "PUREZA",
        "modo": null,
        "modo2": null,
        "modo3": null,
        "modo4": null,
        "modo5": null,
        "moneda": "US",
        "nombre": "DOLAR",
        "notas": null,
        "precio": "200",
        "primCosto": null,
        "pvp": "15",
        "pvp2": null,
        "pvp3": null,
        "pvp4": null,
        "pvp5": null,
        "servicio": "L",
        "status": null,
        "subCateg": null,
        "tamano": null,
        "timeMod": null,
        "tipo": null,
        "ubicacion": null,
        "unidDist1": null,
        "unidDist2": null,
        "whoMod": null
    }
]
```

## `Method POST` /saveProducto
**Crea o actualiza un Producto**

Crea o actualiza la información del Producto indicado.

**Example Input**

```
	
    {
        "productId": null,
        "almacen": "RPD",
        "area": "RP",
        "articulo": "DECORACION",
        "categoria": "HOGAR",
        "codBarra": "12123456878",
        "codRet": null,
        "costo": "200",
        "costoProm": "190",
        "cuenta1": "12365478952",
        "cuenta2": null,
        "cuenta3": null,
        "cuenta4": null,
        "cuenta5": null,
        "grupo": "HOGAR",
        "descPvp": "prom",
        "descPvp2": null,
        "descPvp3": null,
        "descPvp4": null,
        "descPvp5": null,
        "factVenta": "1256",
        "factVenta2": null,
        "factVenta3": null,
        "factVenta4": null,
        "factVenta5": null,
        "forma": "HG",
        "igvcs": null,
        "marca": "PUREZA",
        "medida": null,
        "modelo": "PUREZA",
        "modo": null,
        "modo2": null,
        "modo3": null,
        "modo4": null,
        "modo5": null,
        "moneda": "US",
        "nombre": "DOLAR",
        "notas": null,
        "precio": "200",
        "primCosto": null,
        "pvp": "15",
        "pvp2": null,
        "pvp3": null,
        "pvp4": null,
        "pvp5": null,
        "servicio": "L",
        "status": null,
        "subCateg": null,
        "tamano": null,
        "timeMod": null,
        "tipo": null,
        "ubicacion": null,
        "unidDist1": null,
        "unidDist2": null,
        "whoMod": null
    }

```

**Example Output**

```
	{
		"productId": 3,
		"almacen": "RPD",
		"area": "RP",
		"articulo": "DECORACION",
		"categoria": "HOGAR",
		"codBarra": "12123456878",
		"codRet": null,
		"costo": "200",
		"costoProm": "190",
		"cuenta1": "12365478952",
		"cuenta2": null,
		"cuenta3": null,
		"cuenta4": null,
		"cuenta5": null,
		"grupo": "HOGAR",
		"descPvp": "prom",
		"descPvp2": null,
		"descPvp3": null,
		"descPvp4": null,
		"descPvp5": null,
		"factVenta": "1256",
		"factVenta2": null,
		"factVenta3": null,
		"factVenta4": null,
		"factVenta5": null,
		"forma": "HG",
		"igvcs": null,
		"marca": "PUREZA",
		"medida": null,
		"modelo": "PUREZA",
		"modo": null,
		"modo2": null,
		"modo3": null,
		"modo4": null,
		"modo5": null,
		"moneda": "US",
		"nombre": "DOLAR",
		"notas": null,
		"precio": "200",
		"primCosto": null,
		"pvp": "15",
		"pvp2": null,
		"pvp3": null,
		"pvp4": null,
		"pvp5": null,
		"servicio": "L",
		"status": null,
		"subCateg": null,
		"tamano": null,
		"timeMod": null,
		"tipo": null,
		"ubicacion": null,
		"unidDist1": null,
		"unidDist2": null,
		"whoMod": null
	}

```
## `Method DELETE` /deleteProducto/{idProducto}
**Elimina un producto**

Elimina la información del Producto indicado por su id

**Example Output**

```
[200 OK]
```
