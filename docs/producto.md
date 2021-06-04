---
id: producto
title: API Productos
sidebar_label: API Productos
---

## `Method GET` /productos
**Consulta el listado de productos**

Obtiene el listado de productos existentes

**Example Output**


```
[
    {
        "productId": 13,
        "productsku": "PR-4877",
        "inventario": {
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
        "almacen": "8",
        "area": "8",
        "articulo": "camisa",
        "categoria": "8",
        "codBarra": "8",
        "codRet": "8",
        "costo": 8.0,
        "costoProm": 8.0,
        "cuenta1": "8",
        "cuenta2": "8",
        "cuenta3": "8",
        "cuenta4": "8",
        "cuenta5": "8",
        "grupo": "8",
        "descPvp": "8",
        "descPvp2": "8",
        "descPvp3": "8",
        "descPvp4": "8",
        "descPvp5": "8",
        "factVenta": "8",
        "factVenta2": 8,
        "factVenta3": 8,
        "factVenta4": 8,
        "factVenta5": 8,
        "forma": "8",
        "igvcs": "8",
        "marca": "8",
        "medida": "8",
        "modelo": "8",
        "modo": 8,
        "modo2": 8,
        "modo3": 8,
        "modo4": 8,
        "modo5": 8,
        "moneda": "8",
        "nombre": "8",
        "notas": "8",
        "precio": 8.0,
        "unidad": 8,
        "primCosto": 8.0,
        "pvp": 8,
        "pvp2": 8,
        "pvp3": 8,
        "pvp4": 8,
        "pvp5": 8,
        "servicio": 8,
        "status": "8",
        "subCateg": "8",
        "tamano": "8",
        "timeMod": "8",
        "tipo": "8",
        "ubicacion": "8",
        "unidDist1": 8,
        "unidDist2": 8,
        "whoMod": "8",
        "peso": 8,
        "alto": 8,
        "ancho": 8,
        "imagen": "diario.png"
    },
    {
        "productId": 14,
        "productsku": "PR-4877",
        "inventario": {
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
        "almacen": "8",
        "area": "8",
        "articulo": "camisa",
        "categoria": "8",
        "codBarra": "8",
        "codRet": "8",
        "costo": 8.0,
        "costoProm": 8.0,
        "cuenta1": "8",
        "cuenta2": "8",
        "cuenta3": "8",
        "cuenta4": "8",
        "cuenta5": "8",
        "grupo": "8",
        "descPvp": "8",
        "descPvp2": "8",
        "descPvp3": "8",
        "descPvp4": "8",
        "descPvp5": "8",
        "factVenta": "8",
        "factVenta2": 8,
        "factVenta3": 8,
        "factVenta4": 8,
        "factVenta5": 8,
        "forma": "8",
        "igvcs": "8",
        "marca": "8",
        "medida": "8",
        "modelo": "8",
        "modo": 8,
        "modo2": 8,
        "modo3": 8,
        "modo4": 8,
        "modo5": 8,
        "moneda": "8",
        "nombre": "8",
        "notas": "8",
        "precio": 8.0,
        "unidad": 8,
        "primCosto": 8.0,
        "pvp": 8,
        "pvp2": 8,
        "pvp3": 8,
        "pvp4": 8,
        "pvp5": 8,
        "servicio": 8,
        "status": "8",
        "subCateg": "8",
        "tamano": "8",
        "timeMod": "8",
        "tipo": "8",
        "ubicacion": "8",
        "unidDist1": 8,
        "unidDist2": 8,
        "whoMod": "8",
        "peso": 8,
        "alto": 8,
        "ancho": 8,
        "imagen": "diario.png"
    }
]
```

## `Method GET` /productos/{idProducto}
**Obtiene un producto especifico según el id indicado**

Obtiene un producto especifico según el id indicado

**Example Output**


```
	{
		"productId": 2,
		"productsku": "456",
		"inventario": {
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
		"almacen": "1",
		"area": "1",
		"articulo": "anillo",
		"categoria": "1",
		"codBarra": "1",
		"codRet": "1",
		"costo": 1.0,
		"costoProm": 1.0,
		"cuenta1": "1",
		"cuenta2": "1",
		"cuenta3": "1",
		"cuenta4": "1",
		"cuenta5": "1",
		"grupo": "1",
		"descPvp": "1",
		"descPvp2": "1",
		"descPvp3": "1",
		"descPvp4": "1",
		"descPvp5": "1",
		"factVenta": "1",
		"factVenta2": 1,
		"factVenta3": 1,
		"factVenta4": 1,
		"factVenta5": 1,
		"forma": "1",
		"igvcs": "1",
		"marca": "1",
		"medida": "1",
		"modelo": "1",
		"modo": 1,
		"modo2": 1,
		"modo3": 1,
		"modo4": 1,
		"modo5": 1,
		"moneda": "1",
		"nombre": "pantalon",
		"notas": "1",
		"precio": 105.0,
		"unidad": 123,
		"primCosto": 1.0,
		"pvp": 1,
		"pvp2": 1,
		"pvp3": 1,
		"pvp4": 1,
		"pvp5": 1,
		"servicio": 1,
		"status": "1",
		"subCateg": "1",
		"tamano": "1",
		"timeMod": "1",
		"tipo": "1",
		"ubicacion": "1",
		"unidDist1": 1,
		"unidDist2": 1,
		"whoMod": "1",
		"peso": 345,
		"alto": 567,
		"ancho": 789,
		"imagen": "ilustracion-icono-vector-calendario-amor-concepto-icono-amor_138676-427-removebg-preview.png"
	}
```


## `Method POST` /productos
**Crea o actualiza un Producto**

Crea o actualiza la información del Producto indicado.

**Example Input**

```
	
    {
		"productId": null,
		"productsku": "456",
		"inventario": {
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
		"almacen": "1",
		"area": "1",
		"articulo": "anillo",
		"categoria": "1",
		"codBarra": "1",
		"codRet": "1",
		"costo": 1.0,
		"costoProm": 1.0,
		"cuenta1": "1",
		"cuenta2": "1",
		"cuenta3": "1",
		"cuenta4": "1",
		"cuenta5": "1",
		"grupo": "1",
		"descPvp": "1",
		"descPvp2": "1",
		"descPvp3": "1",
		"descPvp4": "1",
		"descPvp5": "1",
		"factVenta": "1",
		"factVenta2": 1,
		"factVenta3": 1,
		"factVenta4": 1,
		"factVenta5": 1,
		"forma": "1",
		"igvcs": "1",
		"marca": "1",
		"medida": "1",
		"modelo": "1",
		"modo": 1,
		"modo2": 1,
		"modo3": 1,
		"modo4": 1,
		"modo5": 1,
		"moneda": "1",
		"nombre": "pantalon",
		"notas": "1",
		"precio": 105.0,
		"unidad": 123,
		"primCosto": 1.0,
		"pvp": 1,
		"pvp2": 1,
		"pvp3": 1,
		"pvp4": 1,
		"pvp5": 1,
		"servicio": 1,
		"status": "1",
		"subCateg": "1",
		"tamano": "1",
		"timeMod": "1",
		"tipo": "1",
		"ubicacion": "1",
		"unidDist1": 1,
		"unidDist2": 1,
		"whoMod": "1",
		"peso": 345,
		"alto": 567,
		"ancho": 789,
		"imagen": "pen.png"
	}

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /productos/{idProducto}
**Elimina un producto**

Elimina la información del Producto indicado por su id

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
