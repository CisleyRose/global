---
id: almacen
title: API Almacen
sidebar_label: API Almacen
---

## `Method GET` /almacenes
**Consulta el listado de Almacenes**

Obtiene el listado de Almacenes existentes en la empresa

**Example Output**


```
[
    {
        "almacenId": 4,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "nombre": "almacen 4",
        "notas": "sin notas",
        "responsabl": "yaru",
        "timeMod": "1:42:00",
        "ubicacion": "vzla",
        "whoMod": "1254"
    },
    {
        "almacenId": 5,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "nombre": "almacen 5",
        "notas": "sin notas",
        "responsabl": "global",
        "timeMod": "1:42:00",
        "ubicacion": "vzla",
        "whoMod": "1254"
    },
    {
        "almacenId": 3,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "nombre": "almacen 6",
        "notas": "sin notas",
        "responsabl": "global2",
        "timeMod": "1:42:00",
        "ubicacion": "vzla",
        "whoMod": "1254"
    },
    {
        "almacenId": 8,
        "dateMod": "2021-06-03T00:00:00.000+00:00",
        "nombre": "almacen 4",
        "notas": "sin notas",
        "responsabl": "yaru",
        "timeMod": "1:42:00",
        "ubicacion": "vzla",
        "whoMod": "1254"
    }
]
```

## `Method GET` /almacenes/{idAlmacen}
**Obtiene el almacen especifico según el id indicado**

Obtiene el almacen especifico según el id indicado 

**Example Output**


```

    {
		"almacenId": 8,
		"dateMod": "2021-06-03T00:00:00.000+00:00",
		"nombre": "almacen 4",
		"notas": "sin notas",
		"responsabl": "yaru",
		"timeMod": "1:42:00",
		"ubicacion": "vzla",
		"whoMod": "1254"
	}

```

## `Method POST` /almacenes
**Crea o actualiza un Almacen**

Crea o actualiza la información del Almacen indicado.

**Example Input**

```
	
    {
        "almacenId": null,
        "dateMod": "2021-06-03",
        "nombre": "almacen 4",
        "notas": "sin notas",
        "responsabl": "yaru",
        "timeMod": "1:42:00",
        "ubicacion": "vzla",
        "whoMod": "1254"
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /almacenes/{idAlmacen}
**Elimina un Almacen**

Elimina la información del Almacen indicado por su id

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
