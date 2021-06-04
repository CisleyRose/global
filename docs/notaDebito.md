---
id: notaDebito
title: API Notas de Débito
sidebar_label: API Notas de Débito
---

## `Method GET` /enc-debitos
**Obtiene el encabezado de notas de debito de ventas**

Obtiene la información del encabezado de notas de debito de ventas

**Example Output**


```
[
    {
        "encNotaDebitoId": 2,
        "cancelado": 0,
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03T00:00:00.000+00:00",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp",
        "factura": "factura",
        "fecha": "2020-11-03T00:00:00.000+00:00",
        "igvcs": 1,
        "monto": 200.0,
        "montoretiv": 200.0,
        "notadcc": "debito",
        "notas": "notadebito",
        "nsubtotal": 20.0,
        "numcompret": "123",
        "numexp": 1,
        "piva": 1,
        "plazopago": 1,
        "porbase1": 1,
        "porislr": 1,
        "poriva1": 1,
        "proveedor": "global",
        "ptipoimp": "im",
        "retencion": 1,
        "rettodoimp": 1,
        "saldocred": 20.0,
        "timeMod": "11:20:00",
        "tipo": 1,
        "whoMod": "12356"
    },
    {
        "encNotaDebitoId": 3,
        "cancelado": 0,
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03T00:00:00.000+00:00",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp",
        "factura": "factura",
        "fecha": "2020-11-03T00:00:00.000+00:00",
        "igvcs": 1,
        "monto": 200.0,
        "montoretiv": 200.0,
        "notadcc": "debito",
        "notas": "notadebito",
        "nsubtotal": 20.0,
        "numcompret": "123",
        "numexp": 1,
        "piva": 1,
        "plazopago": 1,
        "porbase1": 1,
        "porislr": 1,
        "poriva1": 1,
        "proveedor": "global",
        "ptipoimp": "im",
        "retencion": 1,
        "rettodoimp": 1,
        "saldocred": 20.0,
        "timeMod": "11:20:00",
        "tipo": 1,
        "whoMod": "12356"
    }
]
```

## `Method GET` /enc-debitos/{idEncNotaDebito}
**Obtiene un encabezado de notas de debito de venta según el id indicado**

Obtiene un encabezado de notas de debito de venta según el id indicado

**Example Output**


```
    {
        "encNotaDebitoId": 3,
        "cancelado": 0,
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03T00:00:00.000+00:00",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp",
        "factura": "factura",
        "fecha": "2020-11-03T00:00:00.000+00:00",
        "igvcs": 1,
        "monto": 200.0,
        "montoretiv": 200.0,
        "notadcc": "debito",
        "notas": "notadebito",
        "nsubtotal": 20.0,
        "numcompret": "123",
        "numexp": 1,
        "piva": 1,
        "plazopago": 1,
        "porbase1": 1,
        "porislr": 1,
        "poriva1": 1,
        "proveedor": "global",
        "ptipoimp": "im",
        "retencion": 1,
        "rettodoimp": 1,
        "saldocred": 20.0,
        "timeMod": "11:20:00",
        "tipo": 1,
        "whoMod": "12356"
    }

```

## `Method POST` /enc-debitos
**Crea o actualiza la información del encabezado de notas de debito de ventas**

Crea o actualiza la información del encabezado de notas de debito de ventas.

**Example Input**

```
	
    {
        "encNotaDebitoId": null,
        "cancelado": 0,
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp",
        "factura": "factura",
        "fecha": "2020-11-03",
        "igvcs": 1,
        "monto": 200.0,
        "montoretiv": 200.0,
        "notadcc": "debito",
        "notas": "notadebito",
        "nsubtotal": 20.0,
        "numcompret": "123",
        "numexp": 1,
        "piva": 1,
        "plazopago": 1,
        "porbase1": 1,
        "porislr": 1,
        "poriva1": 1,
        "proveedor": "global",
        "ptipoimp": "im",
        "retencion": 1,
        "rettodoimp": 1,
        "saldocred": 20.0,
        "timeMod": "11:20:00",
        "tipo": 1,
        "whoMod": "12356"
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /enc-debitos/{idEncNotaDebito}
**Elimina un registro del encabezado de notas de debito de ventas**

Elimina la información del encabezado  de notas de debito de ventas

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```

## `Method GET` /det-debitos
**Obtiene el listado de detalles de notas de debito de ventas**

Obtiene la información del detalle de notas de debito de ventas

**Example Output**


```
[
    {
        "encNotaDebitoId": 2,
        "articulo": "pantalon",
        "descripcio": "pantalon",
        "igvcs": 1,
        "montobase": 20.0,
        "notadcc": "debito",
        "proveedor": "global"
    },
    {
        "encNotaDebitoId": 3,
        "articulo": "zapatos",
        "descripcio": "zapatos",
        "igvcs": 1,
        "montobase": 20.0,
        "notadcc": "debito",
        "proveedor": "global"
    }
]

```

## `Method GET` /det-debitos/{idDetNotaDebito}
**Obtiene un detalle de notas de debito de venta según el id indicado**

Obtiene un detalle de notas de debito de venta según el id indicado

**Example Output**


```
    {
        "encNotaDebitoId": 3,
        "articulo": "zapatos",
        "descripcio": "zapatos",
        "igvcs": 1,
        "montobase": 20.0,
        "notadcc": "debito",
        "proveedor": "global"
    }

```

## `Method POST` /det-debitos
**Crea o actualiza la información del detalle de notas de debito de ventas**

Crea o actualiza la información del Detalle de notas de debito de ventas.

**Example Input**

```
	
    {
        "encNotaDebitoId": null,
        "articulo": "zapatos",
        "descripcio": "zapatos",
        "igvcs": 1,
        "montobase": 20.0,
        "notadcc": "debito",
        "proveedor": "global"
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /det-debitos/{idDetNotaDebito}
**Elimina un registro del detalle de notas de debito de ventas**

Elimina la información del detalle de notas de debito de venta especificada

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
