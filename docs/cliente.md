---
id: cliente
title: API Clientes
sidebar_label: API Clientes
---

## `Method GET` /getClientes
**Consulta el listado de clientes**

Obtiene el listado de clientes existentes

**Example Output**


```
[
    {
        "clienteId": 1,
        "aniversar": "123564",
        "cargo": "admin",
        "cliente": "fijo",
        "contacto": "12365478965488",
        "contesp": "a",
        "cxc": "12548",
        "dateMod": "01-09-20",
        "despacho": "domicilio",
        "direccion": "caracas",
        "email": "global@global.com",
        "exc": "erfdfgg",
        "exento": "s",
        "fax": "254896554",
        "limite": "0",
        "montoLim": "500",
        "nit": "158745632",
        "nombre": "global",
        "notas": "sin notas",
        "numPrecio": "1",
        "pais": "vzla",
        "plazoPago": "fij",
        "pvip": "1",
        "tel1": "158874558",
        "tel2": "15478547788",
        "tel3": "145587458",
        "timeMod": "12:52:00",
        "tipoPers": "n",
        "vendedor": "no",
        "whoMod": "548",
        "zip": "147",
        "zona": "vzl"
    },
    {
        "clienteId": 3,
        "aniversar": "222222",
        "cargo": "user",
        "cliente": "fijo",
        "contacto": "12365478965488",
        "contesp": "a",
        "cxc": "12548",
        "dateMod": "01-09-20",
        "despacho": "domicilio",
        "direccion": "caracas",
        "email": "global@global.com",
        "exc": "erfdfgg",
        "exento": "s",
        "fax": "254896554",
        "limite": "0",
        "montoLim": "500",
        "nit": "158745632",
        "nombre": "global",
        "notas": "sin notas",
        "numPrecio": "1",
        "pais": "vzla",
        "plazoPago": "fij",
        "pvip": "1",
        "tel1": "158874558",
        "tel2": "15478547788",
        "tel3": "145587458",
        "timeMod": "12:52:00",
        "tipoPers": "n",
        "vendedor": "no",
        "whoMod": "548",
        "zip": "147",
        "zona": "vzl"
    }
]
```

## `Method POST` /saveCliente
**Crea o actualiza un Cliente**

Crea o actualiza la información del Cliente indicado.

**Example Input**

```
	
     {
        "clienteId": null,
        "aniversar": "2333333",
        "cargo": "user",
        "cliente": "fijo",
        "contacto": "12365478965488",
        "contesp": "a",
        "cxc": "12548",
        "dateMod": "01-09-20",
        "despacho": "domicilio",
        "direccion": "caracas",
        "email": "global@global.com",
        "exc": "erfdfgg",
        "exento": "s",
        "fax": "254896554",
        "limite": "0",
        "montoLim": "500",
        "nit": "158745632",
        "nombre": "global",
        "notas": "sin notas",
        "numPrecio": "1",
        "pais": "vzla",
        "plazoPago": "fij",
        "pvip": "1",
        "tel1": "158874558",
        "tel2": "15478547788",
        "tel3": "145587458",
        "timeMod": "12:52:00",
        "tipoPers": "n",
        "vendedor": "no",
        "whoMod": "548",
        "zip": "147",
        "zona": "vzl"
    }

```

**Example Output**

```
	{
    "clienteId": 5,
    "aniversar": "2333333",
    "cargo": "user",
    "cliente": "fijo",
    "contacto": "12365478965488",
    "contesp": "a",
    "cxc": "12548",
    "dateMod": "01-09-20",
    "despacho": "domicilio",
    "direccion": "caracas",
    "email": "global@global.com",
    "exc": "erfdfgg",
    "exento": "s",
    "fax": "254896554",
    "limite": "0",
    "montoLim": "500",
    "nit": "158745632",
    "nombre": "global",
    "notas": "sin notas",
    "numPrecio": "1",
    "pais": "vzla",
    "plazoPago": "fij",
    "pvip": "1",
    "tel1": "158874558",
    "tel2": "15478547788",
    "tel3": "145587458",
    "timeMod": "12:52:00",
    "tipoPers": "n",
    "vendedor": "no",
    "whoMod": "548",
    "zip": "147",
    "zona": "vzl"
}

```
## `Method DELETE` /deleteCliente/{idCliente}
**Elimina un cliente**

Elimina la información del cliente indicado por su id

**Example Output**

```
[200 OK]
```
