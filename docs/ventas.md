---
id: ventas
title: API Ventas
sidebar_label: API Ventas
---

## `Method GET` /getVentasList
**Consulta el listado de Ventas**

Obtiene el listado de Ventas existentes en la empresa

**Example Output**


```
[
    {
        "ventasId": 1,
        "anombre": "global ventas",
        "arif": "c-895625",
        "caja": "10",
        "cajero": "10",
        "cambio": "sin cambio",
        "cancelado": "1",
        "cliente": "global",
        "control": "control1",
        "controlFin": "contrfin1",
        "dateMod": "2020-09-21T00:00:00.000+00:00",
        "docasoc": "1",
        "dvclie": "global",
        "dvnombre": "global",
        "estado": "v",
        "factura": "factura1",
        "fecha": "2020-09-21T00:00:00.000+00:00",
        "moneda": "us",
        "nigvcs": "1587452",
        "notas": "sin notas",
        "plazoPago": "tri",
        "plinea1": "15874521",
        "plinea2": "587452145",
        "plinea3": "145874525",
        "pmayor": "1",
        "pmontoc": "monto1",
        "pvende": "ve",
        "timeMod": "2020-09-21T00:00:00.000+00:00",
        "ultfact": "ultfact1",
        "vendedor": "ve",
        "whoMod": "159632",
        "nsubTotal": "123654"
    },
    {
        "ventasId": 3,
        "anombre": "global2 ventas",
        "arif": "c-895625",
        "caja": "10",
        "cajero": "10",
        "cambio": "sin cambio",
        "cancelado": "1",
        "cliente": "global",
        "control": "control1",
        "controlFin": "contrfin1",
        "dateMod": "2020-09-21T00:00:00.000+00:00",
        "docasoc": "1",
        "dvclie": "global",
        "dvnombre": "global",
        "estado": "v",
        "factura": "factura1",
        "fecha": "2020-09-21T00:00:00.000+00:00",
        "moneda": "us",
        "nigvcs": "1587452",
        "notas": "sin notas",
        "plazoPago": "tri",
        "plinea1": "15874521",
        "plinea2": "587452145",
        "plinea3": "145874525",
        "pmayor": "1",
        "pmontoc": "monto1",
        "pvende": "ve",
        "timeMod": "2020-09-21T00:00:00.000+00:00",
        "ultfact": "ultfact1",
        "vendedor": "ve",
        "whoMod": "159632",
        "nsubTotal": "123654"
    }
]
```

## `Method POST` /saveVenta
**Crea o actualiza una Venta**

Crea o actualiza la información de la Venta indicada.

**Example Input**

```
	
    {
        "ventasId": null,
        "anombre": "global2 ventas",
        "arif": "c-895625",
        "caja": "10",
        "cajero": "10",
        "cambio": "sin cambio",
        "cancelado": "1",
        "cliente": "global",
        "control": "control1",
        "controlFin": "contrfin1",
        "dateMod": "2020-09-21",
        "docasoc": "1",
        "dvclie": "global",
        "dvnombre": "global",
        "estado": "v",
        "factura": "factura1",
        "fecha": "2020-09-21",
        "moneda": "us",
        "nigvcs": "1587452",
        "notas": "sin notas",
        "plazoPago": "tri",
        "plinea1": "15874521",
        "plinea2": "587452145",
        "plinea3": "145874525",
        "pmayor": "1",
        "pmontoc": "monto1",
        "pvende": "ve",
        "timeMod": "2020-09-21",
        "ultfact": "ultfact1",
        "vendedor": "ve",
        "whoMod": "159632",
        "nsubTotal": "123654"
    }

```

**Example Output**

```
	{
		"ventasId": 3,
		"anombre": "global2 ventas",
		"arif": "c-895625",
		"caja": "10",
		"cajero": "10",
		"cambio": "sin cambio",
		"cancelado": "1",
		"cliente": "global",
		"control": "control1",
		"controlFin": "contrfin1",
		"dateMod": "2020-09-21T00:00:00.000+00:00",
		"docasoc": "1",
		"dvclie": "global",
		"dvnombre": "global",
		"estado": "v",
		"factura": "factura1",
		"fecha": "2020-09-21T00:00:00.000+00:00",
		"moneda": "us",
		"nigvcs": "1587452",
		"notas": "sin notas",
		"plazoPago": "tri",
		"plinea1": "15874521",
		"plinea2": "587452145",
		"plinea3": "145874525",
		"pmayor": "1",
		"pmontoc": "monto1",
		"pvende": "ve",
		"timeMod": "2020-09-21T00:00:00.000+00:00",
		"ultfact": "ultfact1",
		"vendedor": "ve",
		"whoMod": "159632",
		"nsubTotal": "123654"
	}

```
## `Method DELETE` /deleteVenta/{idVenta}
**Elimina una Venta**

Elimina la información de la Venta indicada

**Example Output**

```
[200 OK]
```
