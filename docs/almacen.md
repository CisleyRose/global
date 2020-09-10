---
id: almacen
title: API Almacen
sidebar_label: API Almacen
---

## `Method GET` /getAlmacenList
**Consulta el listado de Almacenes**

Obtiene el listado de Almacenes existentes en la empresa

**Example Output**


```
[
    {
        "almacenId": 1,
        "dateMod": "2020-09-09T00:00:00.000+00:00",
        "nombre": "Global",
        "notas": "Sin notas",
        "responsabl": "Admin",
        "timeMod": "2:28:00",
        "ubicacion": "Vz",
        "whoMod": "123"
    }
]
```

## `Method POST` /saveAlmacen
**Crea o actualiza un Almacen**

Crea o actualiza la información del Almacen indicado.

**Example Input**

```
	
    {
		"almacenId": null,
		"dateMod": "2020-09-09T00:00:00.000+00:00",
		"nombre": "User",
		"notas": "Con notas",
		"responsabl": "User",
		"timeMod": "2:36:00",
		"ubicacion": "CL",
		"whoMod": "1234"
	}

```

**Example Output**

```
	{
		"almacenId": 3,
		"dateMod": "2020-09-09T00:00:00.000+00:00",
		"nombre": "User",
		"notas": "Con notas",
		"responsabl": "User",
		"timeMod": "2:36:00",
		"ubicacion": "CL",
		"whoMod": "1234"
	}

```
## `Method DELETE` /deleteAlmacen/{idAlmacen}
**Elimina un Almacen**

Elimina la información del Almacen indicado por su id

**Example Output**

```
[200 OK]
```
