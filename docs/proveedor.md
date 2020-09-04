---
id: proveedor
title: API Proveedores
sidebar_label: API Proveedores
---

## `Method GET` /getProveedores
**Consulta el listado de proveedores**

Obtiene el listado de proveedores existentes

**Example Output**


```
[
    {
        "proveedorId": 1,
        "cargo": "admin",
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
]
```

## `Method POST` /saveProveedor
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
	{
		"proveedorId": 4,
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
## `Method DELETE` /deleteProveedor/{idProveedor}
**Elimina un proveedor**

Elimina la información del proveedor indicado por su id

**Example Output**

```
[200 OK]
```
