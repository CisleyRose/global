---
id: notaCredito
title: API Notas de Crédito
sidebar_label: API Notas de Crédito
---

## `Method GET` /enc-creditos
**Obtiene el encabezado de notas de credito de ventas**

Obtiene la información del encabezado de notas de credito de ventas

**Example Output**


```
[
    {
        "encNotaCreditoId": 2,
        "cancelado": 0,
        "cliente": "global",
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03T00:00:00.000+00:00",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp1",
        "factura": "factura",
        "fecha": "2020-11-03T00:00:00.000+00:00",
        "igvcs": 1,
        "monto": 200.0,
        "notadcv": "credito",
        "notas": "notas",
        "numexc": 1,
        "piva": 1,
        "plazopago": 1,
        "pomite": 1,
        "ptipoimp": "im",
        "saldocred": 100.0,
        "timeMod": "11:13:00",
        "tipo": 1,
        "ultnota": "notault",
        "whoMod": "1234"
    },
    {
        "encNotaCreditoId": 3,
        "cancelado": 0,
        "cliente": "global",
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03T00:00:00.000+00:00",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp1",
        "factura": "factura",
        "fecha": "2020-11-03T00:00:00.000+00:00",
        "igvcs": 1,
        "monto": 200.0,
        "notadcv": "credito",
        "notas": "notas",
        "numexc": 1,
        "piva": 1,
        "plazopago": 1,
        "pomite": 1,
        "ptipoimp": "im",
        "saldocred": 100.0,
        "timeMod": "11:13:00",
        "tipo": 1,
        "ultnota": "notault",
        "whoMod": "1234"
    }
]
```

## `Method GET` /enc-creditos/{idEncNotaCredito}
**Obtiene un encabezado de notas de credito de venta según el id indicado**

Obtiene un encabezado de notas de credito de venta según el id indicado

**Example Output**


```
    {
        "encNotaCreditoId": 3,
        "cancelado": 0,
        "cliente": "global",
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03T00:00:00.000+00:00",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp1",
        "factura": "factura",
        "fecha": "2020-11-03T00:00:00.000+00:00",
        "igvcs": 1,
        "monto": 200.0,
        "notadcv": "credito",
        "notas": "notas",
        "numexc": 1,
        "piva": 1,
        "plazopago": 1,
        "pomite": 1,
        "ptipoimp": "im",
        "saldocred": 100.0,
        "timeMod": "11:13:00",
        "tipo": 1,
        "ultnota": "notault",
        "whoMod": "1234"
    }

```


## `Method POST` /enc-creditos
**Crea o actualiza la información del encabezado de notas de credito de ventas**

Crea o actualiza la información del encabezado de notas de credito de ventas.

**Example Input**

```
	
    {
        "encNotaCreditoId": null,
        "cancelado": 0,
        "cliente": "global",
        "control": 1,
        "controlFin": 1,
        "dateMod": "2020-11-03",
        "docasoc": 1,
        "estado": 1,
        "exp": "exp1",
        "factura": "factura",
        "fecha": "2020-11-03",
        "igvcs": 1,
        "monto": 200.0,
        "notadcv": "credito",
        "notas": "notas",
        "numexc": 1,
        "piva": 1,
        "plazopago": 1,
        "pomite": 1,
        "ptipoimp": "im",
        "saldocred": 100.0,
        "timeMod": "11:13:00",
        "tipo": 1,
        "ultnota": "notault",
        "whoMod": "1234"
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /enc-creditos/{idEncNotaCredito}
**Elimina un registro del encabezado de notas de credito de ventas**

Elimina la información del encabezado  de notas de credito de ventas

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```

## `Method GET` /det-creditos
**Obtiene el listado de detalles de notas de credito de ventas**

Obtiene la información del detalle de notas de credito de ventas

**Example Output**


```
[
    {
        "detNotaCreditoId": 2,
        "articulo": "silla",
        "descripcio": "silla",
        "igvcs": 1,
        "montobase": 50.0,
        "notadcv": "credito"
    },
    {
        "detNotaCreditoId": 3,
        "articulo": "mesa",
        "descripcio": "mesa",
        "igvcs": 1,
        "montobase": 50.0,
        "notadcv": "credito"
    }
]

```

## `Method GET` /det-creditos/{idDetNotaCredito}
**Obtiene el listado un detalle de notas de credito de venta según el id indicado**

Obtiene el listado un detalle de notas de credito de venta según el id indicado

**Example Output**


```
    {
        "detNotaCreditoId": 2,
        "articulo": "silla",
        "descripcio": "silla",
        "igvcs": 1,
        "montobase": 50.0,
        "notadcv": "credito"
    }
```

## `Method POST` /det-creditos
**Crea o actualiza la información del detalle de notas de credito de ventas**

Crea o actualiza la información del Detalle de notas de credito de ventas.

**Example Input**

```
	
    {
        "detNotaCreditoId": null,
        "articulo": "mesa",
        "descripcio": "mesa",
        "igvcs": 1,
        "montobase": 50.0,
        "notadcv": "credito"
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /det-creditos/{idDetNotaCredito}
**Elimina un registro del detalle de notas de credito de ventas**

Elimina la información del detalle de notas de credito de venta especificada

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
