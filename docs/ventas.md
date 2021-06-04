---
id: ventas
title: API Ventas
sidebar_label: API Ventas
---

## `Method GET` /ventas
**Consulta el listado de Ventas**

Obtiene el listado de Ventas existentes en la empresa

**Example Output**


```
[
    {
        "ventasId": 3,
        "cliente": {
            "clienteId": 1,
            "numIdenti": 1,
            "aniversar": "2021-04-22T00:00:00.000+00:00",
            "cargo": "1",
            "cliente": "1",
            "contacto": "1",
            "contesp": 1,
            "cxc": "1",
            "dateMod": "2021-04-22T00:00:00.000+00:00",
            "despacho": "1",
            "direccion": "global2",
            "email": "1",
            "exc": "1",
            "exento": 1,
            "fax": "1",
            "limite": 1,
            "montoLim": 1.0,
            "nit": "1",
            "nombre": "global",
            "notas": "1",
            "numPrecio": "1",
            "pais": "1",
            "plazoPago": 1,
            "pvip": 1,
            "tel1": "1",
            "tel2": "1",
            "tel3": "1",
            "timeMod": "1",
            "tipoPers": 1,
            "vendedor": "1",
            "whoMod": "1",
            "zip": "1",
            "zona": "1"
        },
        "anombre": "3",
        "arif": "3",
        "caja": "3",
        "cajero": "3",
        "cambio": 3,
        "cancelado": 3,
        "control": 3,
        "controlFin": 3,
        "dateMod": "2021-05-17T14:23:00.000+00:00",
        "docasoc": 3,
        "dvclie": 3,
        "dvnombre": "3",
        "estado": 3,
        "factura": "3",
        "fecha": "2021-05-17T14:24:00.000+00:00",
        "moneda": "3",
        "nigvcs": 3,
        "notas": "3",
        "plazoPago": 3,
        "plinea1": "3",
        "plinea2": "3",
        "plinea3": "3",
        "pmayor": 3,
        "pmontoc": 3,
        "pvende": "3",
        "timeMod": "2021-05-17T14:24:00.000+00:00",
        "ultfact": "3",
        "vendedor": "3",
        "whoMod": "3",
        "producto": null,
        "nsubTotal": 3
    },
    {
        "ventasId": 4,
        "cliente": {
            "clienteId": 2,
            "numIdenti": 1,
            "aniversar": "2021-04-22T00:00:00.000+00:00",
            "cargo": "1",
            "cliente": "1",
            "contacto": "1",
            "contesp": 1,
            "cxc": "1",
            "dateMod": "2021-04-22T00:00:00.000+00:00",
            "despacho": "1",
            "direccion": "1",
            "email": "1",
            "exc": "1",
            "exento": 1,
            "fax": "1",
            "limite": 1,
            "montoLim": 1.0,
            "nit": "1",
            "nombre": "yaruby",
            "notas": "1",
            "numPrecio": "1",
            "pais": "1",
            "plazoPago": 1,
            "pvip": 1,
            "tel1": "1",
            "tel2": "1",
            "tel3": "1",
            "timeMod": "1",
            "tipoPers": 1,
            "vendedor": "1",
            "whoMod": "1",
            "zip": "1",
            "zona": null
        },
        "anombre": "1",
        "arif": "1",
        "caja": "1",
        "cajero": "1",
        "cambio": 1,
        "cancelado": 1,
        "control": 1,
        "controlFin": 1,
        "dateMod": "2021-05-20T13:28:00.000+00:00",
        "docasoc": 1,
        "dvclie": 1,
        "dvnombre": "1",
        "estado": 1,
        "factura": "1",
        "fecha": "2021-05-20T13:28:00.000+00:00",
        "moneda": "1",
        "nigvcs": 1,
        "notas": "1",
        "plazoPago": 1,
        "plinea1": "1",
        "plinea2": "1",
        "plinea3": "1",
        "pmayor": 1,
        "pmontoc": 1,
        "pvende": "1",
        "timeMod": "2021-05-20T13:28:00.000+00:00",
        "ultfact": "1",
        "vendedor": "1",
        "whoMod": "1",
        "producto": "6",
        "nsubTotal": 1
    }
]
```

## `Method GET` /ventas/{idVenta}
**Obtiene la venta indicada según el id especificado**

Obtiene la venta indicada según el id especificado

**Example Output**


```
	{
		"ventasId": 3,
		"cliente": {
			"clienteId": 1,
			"numIdenti": 1,
			"aniversar": "2021-04-22T00:00:00.000+00:00",
			"cargo": "1",
			"cliente": "1",
			"contacto": "1",
			"contesp": 1,
			"cxc": "1",
			"dateMod": "2021-04-22T00:00:00.000+00:00",
			"despacho": "1",
			"direccion": "global2",
			"email": "1",
			"exc": "1",
			"exento": 1,
			"fax": "1",
			"limite": 1,
			"montoLim": 1.0,
			"nit": "1",
			"nombre": "global",
			"notas": "1",
			"numPrecio": "1",
			"pais": "1",
			"plazoPago": 1,
			"pvip": 1,
			"tel1": "1",
			"tel2": "1",
			"tel3": "1",
			"timeMod": "1",
			"tipoPers": 1,
			"vendedor": "1",
			"whoMod": "1",
			"zip": "1",
			"zona": "1"
		},
		"anombre": "3",
		"arif": "3",
		"caja": "3",
		"cajero": "3",
		"cambio": 3,
		"cancelado": 3,
		"control": 3,
		"controlFin": 3,
		"dateMod": "2021-05-17T14:23:00.000+00:00",
		"docasoc": 3,
		"dvclie": 3,
		"dvnombre": "3",
		"estado": 3,
		"factura": "3",
		"fecha": "2021-05-17T14:24:00.000+00:00",
		"moneda": "3",
		"nigvcs": 3,
		"notas": "3",
		"plazoPago": 3,
		"plinea1": "3",
		"plinea2": "3",
		"plinea3": "3",
		"pmayor": 3,
		"pmontoc": 3,
		"pvende": "3",
		"timeMod": "2021-05-17T14:24:00.000+00:00",
		"ultfact": "3",
		"vendedor": "3",
		"whoMod": "3",
		"producto": null,
		"nsubTotal": 3
	}
```


## `Method POST` /ventas
**Crea o actualiza una Venta**

Crea o actualiza la información de la Venta indicada.

**Example Input**

```
	
    {
		"ventasId": 3,
		"cliente": {
			"clienteId": 1,
			"numIdenti": 1,
			"aniversar": "2021-04-22",
			"cargo": "1",
			"cliente": "1",
			"contacto": "1",
			"contesp": 1,
			"cxc": "1",
			"dateMod": "2021-04-22",
			"despacho": "1",
			"direccion": "global2",
			"email": "1",
			"exc": "1",
			"exento": 1,
			"fax": "1",
			"limite": 1,
			"montoLim": 1.0,
			"nit": "1",
			"nombre": "global",
			"notas": "1",
			"numPrecio": "1",
			"pais": "1",
			"plazoPago": 1,
			"pvip": 1,
			"tel1": "1",
			"tel2": "1",
			"tel3": "1",
			"timeMod": "1",
			"tipoPers": 1,
			"vendedor": "1",
			"whoMod": "1",
			"zip": "1",
			"zona": "1"
		},
		"anombre": "3",
		"arif": "3",
		"caja": "3",
		"cajero": "3",
		"cambio": 3,
		"cancelado": 3,
		"control": 3,
		"controlFin": 3,
		"dateMod": "2021-05-17",
		"docasoc": 3,
		"dvclie": 3,
		"dvnombre": "3",
		"estado": 3,
		"factura": "3",
		"fecha": "2021-05-17",
		"moneda": "3",
		"nigvcs": 3,
		"notas": "3",
		"plazoPago": 3,
		"plinea1": "3",
		"plinea2": "3",
		"plinea3": "3",
		"pmayor": 3,
		"pmontoc": 3,
		"pvende": "3",
		"timeMod": "2021-05-17",
		"ultfact": "3",
		"vendedor": "3",
		"whoMod": "3",
		"producto": "toalla",
		"nsubTotal": 3
	}

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /ventas/{idVenta}
**Elimina una Venta**

Elimina la información de la Venta indicada

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
