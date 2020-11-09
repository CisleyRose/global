---
id: cotizacion
title: API Cotizacion
sidebar_label: API Cotizacion
---

## `Method GET` /getVcotizaList
**Obtiene el encabezado de cotizaciones**

Obtiene la información del encabezado de cotizaciones 

**Example Output**


```
[
	{
        "vcotizaId": 2,
        "cambio": 2,
        "cliente": "andres",
        "cotizacion": 74125598,
        "datemod": "2021-04-21T00:00:00.000+00:00",
        "estado": 2,
        "fecha": "2021-08-24T00:00:00.000+00:00",
        "moneda": "us",
        "notas": "reenganche",
        "timemod": "06:24:44",
        "vigencia": 4500,
        "whomode": "luan"
    },
]
```

## `Method POST` /saveVcotiza
**Crea o actualiza la información del encabezado de cotizaciones**

Crea o actualiza la información del encabezado de cotizaciones

**Example Input**

```

{
    "vcotizaId": null,
    "cambio": 4,
    "cliente": "juan",
    "cotizacion": 24468579,
    "datemod": "2021-01-10T00:00:00.000+00:00",
    "estado": 1,
    "fecha": "2020-12-12T00:00:00.000+00:00",
    "moneda": "eu",
    "notas": "ingreso",
    "timemod": "10:30:21",
    "vigencia": 2100,
    "whomode": "gabriela"
}
	
```

**Example Output**

```
{
	"vcotizaId": 4,
    "cambio": 4,
    "cliente": "juan",
    "cotizacion": 24468579,
    "datemod": "2021-01-10T00:00:00.000+00:00",
    "estado": 1,
    "fecha": "2020-12-12T00:00:00.000+00:00",
    "moneda": "eu",
    "notas": "ingreso",
    "timemod": "10:30:21",
    "vigencia": 2100,
    "whomode": "gabriela"
}

```
## `Method DELETE` /deleteVcotiza/{idVcotiza}
**Elimina un registro del encabezado de cotizaciones**

Elimina la información del encabezado de cotizaciones

**Example Output**

```
[200 OK]
```

## `Method GET` /getVcotizadList
**Obtiene el listado de las ventas cotizadas**

Obtiene la información de las ventas cotizadas

**Example Output**

```
[
    {
        "vcotizadId": 2,
        "articulo": "monitor50plg",
        "cantidad": 504.22,
        "cotizacion": 23468579,
        "descmonto": 250.11,
        "descripcio": "Monitor",
        "descuento": 49.2,
        "entrega": 122,
        "facturado": 30.55,
        "garantia": 90,
        "igvcs": 124.16,
        "item": 1,
        "itemdoc": "null",
        "numprecio": 2,
        "precio": 9000
    }
]

```
## `Method POST` /saveVcotizad
**Crea o actualiza la información de las ventas cotizadas**

Crea o actualiza la información de las ventas cotizadas

**Example Input**

```
{
        "vcotizadId": null,
        "articulo": "cpui5intel",
        "cantidad": 230.00,
        "cotizacion": 40126398,
        "descmonto": 125.00,
        "descripcio": "Cpu c/ i5",
        "descuento": 37.5,
        "entrega": 166,
        "facturado": 45.22,
        "garantia": 120,
        "igvcs": 90.12,
        "item": 2,
        "itemdoc": "null",
        "numprecio": 3,
        "precio": 4500
}

```

**Example Output**

```

{
    "vcotizadId": 3,
    "articulo": "cpui5intel",
    "cantidad": 230.0,
    "cotizacion": 40126398,
    "descmonto": 125.0,
    "descripcio": "Cpu c/ i5",
    "descuento": 37.5,
    "entrega": 166,
    "facturado": 45.22,
    "garantia": 120,
    "igvcs": 90.12,
    "item": 2,
    "itemdoc": "null",
    "numprecio": 3,
    "precio": 4500
}

```
## `Method DELETE` /deleteVcotizad/{idVcotizad}
**Elimina un registro del detalle de las ventas cotizadas**

Elimina la información del detalle de las ventas cotizadas

**Example Output**

```
[200 OK]
```
