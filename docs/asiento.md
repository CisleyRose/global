---
id: asiento
title: API Asientos Contables
sidebar_label: API Asientos Contables
---

## `Method GET` /enc-asientos
**Obtiene el encabezado de asientos contables**

Obtiene la información del encabezado de asientos contables

**Example Output**


```
[
    {
        "encasienContId": 1,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "descripcio": "ahorro",
        "documento": "documento 1",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "numero": "1258",
        "timeMod": "1:42:00",
        "tipcomp": "AHO",
        "whoMod": "158"
    },
    {
        "encasienContId": 2,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "descripcio": "ahorro",
        "documento": "documento 2",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "numero": "1258",
        "timeMod": "1:42:00",
        "tipcomp": "AHO",
        "whoMod": "158"
    },
    {
        "encasienContId": 3,
        "dateMod": "2021-05-26T00:00:00.000+00:00",
        "descripcio": "corriente",
        "documento": "documento 3",
        "estado": 1,
        "fecha": "2021-05-26T00:00:00.000+00:00",
        "numero": "1258",
        "timeMod": "1:42:00",
        "tipcomp": "CRR",
        "whoMod": "158"
    }
]
```

## `Method GET` /enc-asientos/{idEncAsienCont}
**Obtiene el encabezado de un asiento contable especifico según el id indicado**

Obtiene la información de un encabezado de un asiento contable especifico según el id indicado

**Example Output**


```
	{
		"encasienContId": 3,
		"dateMod": "2021-05-26T00:00:00.000+00:00",
		"descripcio": "corriente",
		"documento": "documento 3",
		"estado": 1,
		"fecha": "2021-05-26T00:00:00.000+00:00",
		"numero": "1258",
		"timeMod": "1:42:00",
		"tipcomp": "CRR",
		"whoMod": "158"
	}
```

## `Method POST` /enc-asientos
**Crea o actualiza la información del encabezado de los asientos contables**

Crea o actualiza la información del encabezado del asiento contable especificado.

**Example Input**

```
	
    {
		"encasienContId": null,
		"dateMod": "2021-06-03",
		"descripcio": "corriente",
		"documento": "documento 3",
		"estado": 1,
		"fecha": "2021-06-03",
		"numero": "1258",
		"timeMod": "1:42:00",
		"tipcomp": "CRR",
		"whoMod": "158"
	}

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /enc-asientos/{idEncAsienCont}
**Elimina un registro del encabezado de los asientos contables**

Elimina la información del encabezado del asiento contable especificado especificado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```

## `Method GET` /det-asientos
**Obtiene el listado de detalles de los asientos contables**

Obtiene la información del detalle de los asientos contables

**Example Output**


```
[
    
    {
        "detasienContId": 1,
        "creditos": 1258,
        "cuenta": "ahorro",
        "debitos": 854,
        "descrip": "debito",
        "grupo": "B",
        "item": "item2",
        "numero": "14858745",
        "referencia": "A-0983",
        "tipo": "001",
        "unidad": "Unit1"
    },
    {
        "detasienContId": 2,
        "creditos": 1258,
        "cuenta": "ahorro",
        "debitos": 854,
        "descrip": "debito",
        "grupo": "B",
        "item": "item3",
        "numero": "14858745",
        "referencia": "A-0983",
        "tipo": "001",
        "unidad": "Unit2"
    },
    {
        "detasienContId": 3,
        "creditos": 1259,
        "cuenta": "ahorro",
        "debitos": 854,
        "descrip": "debito",
        "grupo": "B",
        "item": "item2",
        "numero": "14858745",
        "referencia": "A-0983",
        "tipo": "001",
        "unidad": "Unit3"
    }
]

```

## `Method GET` /det-asientos/{idDetAsienCont}
**Obtiene el detalle de un asiento contable especifico según el id indicado**

Obtiene la información del detalle de los asientos contables según el id indicado

**Example Output**


```
	{
		"detasienContId": 3,
		"creditos": 1259,
		"cuenta": "ahorro",
		"debitos": 854,
		"descrip": "debito",
		"grupo": "B",
		"item": "item2",
		"numero": "14858745",
		"referencia": "A-0983",
		"tipo": "001",
		"unidad": "Unit3"
	}

```

## `Method POST` /det-asientos
**Crea o actualiza la información del detalle del asiento contable**

Crea o actualiza la información del Detalle del asiento contable especificada.

**Example Input**

```
	
    {
		"detasienContId": null,
		"creditos": 1259,
		"cuenta": "ahorro",
		"debitos": 854,
		"descrip": "debito",
		"grupo": "B",
		"item": "item2",
		"numero": "14858745",
		"referencia": "A-0983",
		"tipo": "001",
		"unidad": "Unit3"
	}

```

**Example Output**

```
[201 OK]

```
## `Method DELETE` /det-asientos/{idDetAsienCont}
**Elimina un registro del detalle de los asientos contables**

Elimina la información del detalle del asiento contable especificado especificado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
