---
id: proveedor
title: API Proveedores
sidebar_label: API Proveedores
---

## `Method GET` /proveedores
**Consulta el listado de proveedores**

Obtiene el listado de proveedores existentes

**Example Output**


```
[
    {
        "proveedorId": 2,
        "cargo": "desarrollador",
        "ciudad": "cl",
        "contacto": "contacto",
        "contesp": 1,
        "cxc": "cxc",
        "dateMod": "2021-05-28T00:00:00.000+00:00",
        "direccion": "santiago",
        "email": "global@global.com",
        "exp": "exp",
        "extranjero": 0,
        "fax": "fax",
        "moneda": "pe",
        "nit": "14785",
        "nombre": "luis",
        "notas": "sin notas",
        "pais": "cl",
        "proveedor": "global",
        "ptipo": 2,
        "tel1": "147854",
        "tel2": "147852",
        "tel3": "1478547",
        "timeMod": "6:30:00",
        "tipoPers": 3,
        "whoMod": "1452",
        "zip": "zip"
    },
    {
        "proveedorId": 3,
        "cargo": "qa",
        "ciudad": "cl",
        "contacto": "contacto",
        "contesp": 1,
        "cxc": "cxc",
        "dateMod": "2021-05-28T00:00:00.000+00:00",
        "direccion": "santiago",
        "email": "global@global.com",
        "exp": "exp",
        "extranjero": 0,
        "fax": "fax",
        "moneda": "pe",
        "nit": "14785",
        "nombre": "luis",
        "notas": "sin notas",
        "pais": "cl",
        "proveedor": "global",
        "ptipo": 2,
        "tel1": "147854",
        "tel2": "147852",
        "tel3": "1478547",
        "timeMod": "6:30:00",
        "tipoPers": 3,
        "whoMod": "1452",
        "zip": "zip"
    }
]
```

## `Method GET` /proveedores/{idProveedor}
**Obtiene un proveedor especifico según el id indicado**

Obtiene un proveedor especifico según el id indicado

**Example Output**


```
[
    {
        "proveedorId": 3,
        "cargo": "qa",
        "ciudad": "cl",
        "contacto": "contacto",
        "contesp": 1,
        "cxc": "cxc",
        "dateMod": "2021-05-28T00:00:00.000+00:00",
        "direccion": "santiago",
        "email": "global@global.com",
        "exp": "exp",
        "extranjero": 0,
        "fax": "fax",
        "moneda": "pe",
        "nit": "14785",
        "nombre": "luis",
        "notas": "sin notas",
        "pais": "cl",
        "proveedor": "global",
        "ptipo": 2,
        "tel1": "147854",
        "tel2": "147852",
        "tel3": "1478547",
        "timeMod": "6:30:00",
        "tipoPers": 3,
        "whoMod": "1452",
        "zip": "zip"
    }
]
```

## `Method POST` /proveedores
**Crea o actualiza un Proveedor**

Crea o actualiza la información del Proveedor indicado.

**Example Input**

```
	
    {
        "proveedorId": null,
        "cargo": "new",
        "ciudad": "csc",
        "contacto": "1547854",
        "contesp": "1",
        "cxc": "1548669",
        "dateMod": "01-09-20",
        "direccion": "caracas",
        "email": "global@global.com",
        "exp": "1547895",
        "extranjero": "s",
        "fax": "15487855",
        "moneda": "us",
        "nit": "14785478",
        "nombre": "global",
        "notas": "sin notas",
        "pais": "vzla",
        "proveedor": "globalTota",
        "ptipo": "1",
        "tel1": "15963855",
        "tel2": "258965244",
        "tel3": "358874458",
        "timeMod": "12:59:00",
        "tipoPers": "n",
        "whoMod": "562",
        "zip": "147"
    }

```

**Example Output**

```
[201 OK]
```
## `Method DELETE` /proveedores/{idProveedor}
**Elimina un proveedor**

Elimina la información del proveedor indicado por su id

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
