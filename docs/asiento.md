---
id: asiento
title: API Asientos Contables
sidebar_label: API Asientos Contables
---

## `Method GET` /getEncAsienContList
**Obtiene el encabezado de asientos contables**

Obtiene la información del encabezado de asientos contables

**Example Output**


```
[
    {
        "encasienContId": 2,
        "dateMod": "2020-10-21T00:00:00.000+00:00",
        "descripcio": "asientos contables",
        "documento": "documento2",
        "estado": 1,
        "fecha": "2020-10-21T00:00:00.000+00:00",
        "numero": "125874255",
        "timeMod": "10:30:15",
        "tipcomp": "com",
        "whoMod": "1236985214"
    },
    {
        "encasienContId": 3,
        "dateMod": "2020-10-21T00:00:00.000+00:00",
        "descripcio": "asientos contables",
        "documento": "documento2",
        "estado": 1,
        "fecha": "2020-10-21T00:00:00.000+00:00",
        "numero": "125874255",
        "timeMod": "10:30:15",
        "tipcomp": "com",
        "whoMod": "1236985214"
    }
]
```

## `Method POST` /saveEncAsienCont
**Crea o actualiza la información del encabezado de los asientos contables**

Crea o actualiza la información del encabezado del asiento contable especificado.

**Example Input**

```
	
    {
        "encasienContId": null,
        "dateMod": "2020-10-21",
        "descripcio": "asientos contables",
        "documento": "documento2",
        "estado": 1,
        "fecha": "2020-10-21",
        "numero": "125874255",
        "timeMod": "10:30:15",
        "tipcomp": "com",
        "whoMod": "1236985214"
    }

```

**Example Output**

```
	{
		"encasienContId": 3,
		"dateMod": "2020-10-21T00:00:00.000+00:00",
		"descripcio": "asientos contables",
		"documento": "documento2",
		"estado": 1,
		"fecha": "2020-10-21T00:00:00.000+00:00",
		"numero": "125874255",
		"timeMod": "10:30:15",
		"tipcomp": "com",
		"whoMod": "1236985214"
	}

```
## `Method DELETE` /deleteEncAsienCont/{idEncAsienCont}
**Elimina un registro del encabezado de los asientos contables**

Elimina la información del encabezado del asiento contable especificado especificado

**Example Output**

```
[200 OK]
```

## `Method GET` /getDetAsienContList
**Obtiene el listado de detalles de los asientos contables**

Obtiene la información del detalle de los asientos contables

**Example Output**


```
[
    {
        "detasienContId": 2,
        "creditos": 12,
        "cuenta": "123445677",
        "debitos": 12,
        "descrip": "asientos contables",
        "grupo": "asientos1",
        "item": "asien",
        "numero": "1236587452",
        "referencia": "asientos",
        "tipo": "123",
        "unidad": "unidad"
    },
    {
        "detasienContId": 3,
        "creditos": 12,
        "cuenta": "123445677",
        "debitos": 12,
        "descrip": "asientos contables",
        "grupo": "asientos1",
        "item": "asien",
        "numero": "1236587452",
        "referencia": "asientos",
        "tipo": "123",
        "unidad": "unidad"
    }
]
```

## `Method POST` /saveDetAsienCont
**Crea o actualiza la información del detalle del asiento contable**

Crea o actualiza la información del Detalle del asiento contable especificada.

**Example Input**

```
	
    {
        "detasienContId": null,
        "creditos": 12,
        "cuenta": "123445677",
        "debitos": 12,
        "descrip": "asientos contables",
        "grupo": "asientos1",
        "item": "asien",
        "numero": "1236587452",
        "referencia": "asientos",
        "tipo": "123",
        "unidad": "unidad"
    }

```

**Example Output**

```
	{
		"detasienContId": 3,
		"creditos": 12,
		"cuenta": "123445677",
		"debitos": 12,
		"descrip": "asientos contables",
		"grupo": "asientos1",
		"item": "asien",
		"numero": "1236587452",
		"referencia": "asientos",
		"tipo": "123",
		"unidad": "unidad"
	}

```
## `Method DELETE` /deleteDetAsienCont/{idDetAsienCont}
**Elimina un registro del detalle de los asientos contables**

Elimina la información del detalle del asiento contable especificado especificado

**Example Output**

```
[200 OK]
```
