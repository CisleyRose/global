---
id: cuentasBancarias
title: API Cuentas Bancarias
sidebar_label: API Cuentas Bancarias
---

## `Method GET` /cuentas-bancarias
**Obtiene el listado de los datos de cuentas bancarias**

Obtiene la información de las cuentas bancarias existentes en la empresa

**Example Output**


```
[
    {
        "cuentaBancariaId": 1,
        "apertura": "2020-10-08T00:00:00.000+00:00",
        "banco": "vz",
        "cierre": "2021-10-08T00:00:00.000+00:00",
        "cuenta": 1236547,
        "cuentaCont": "corriente",
        "dateMod": "2020-10-06T00:00:00.000+00:00",
        "descripcio": "cuenta empresarial",
        "genMovImp": 1,
        "moneda": "us",
        "notas": "con notas",
        "nroCuenta": "12365478963258741",
        "timeMod": "06102020",
        "tipo": "01",
        "uso": "01",
        "whoMod": "1236528"
    },
    {
        "cuentaBancariaId": 2,
        "apertura": "2020-10-08T00:00:00.000+00:00",
        "banco": "vz",
        "cierre": "2021-10-08T00:00:00.000+00:00",
        "cuenta": 1236547,
        "cuentaCont": "corriente",
        "dateMod": "2020-10-06T00:00:00.000+00:00",
        "descripcio": "cuenta empresarial",
        "genMovImp": 1,
        "moneda": "us",
        "notas": "con notas",
        "nroCuenta": "12365478963258741",
        "timeMod": "06102020",
        "tipo": "01",
        "uso": "01",
        "whoMod": "1236528"
    }
]
```

## `Method GET` /cuentas-bancarias/{idCuentaBancaria}
**Obtiene una cuenta bancaria especifica según el id indicado**

Obtiene una cuenta bancaria especifica según el id indicado
**Example Output**


```
    {
        "cuentaBancariaId": 2,
        "apertura": "2020-10-08T00:00:00.000+00:00",
        "banco": "vz",
        "cierre": "2021-10-08T00:00:00.000+00:00",
        "cuenta": 1236547,
        "cuentaCont": "corriente",
        "dateMod": "2020-10-06T00:00:00.000+00:00",
        "descripcio": "cuenta empresarial",
        "genMovImp": 1,
        "moneda": "us",
        "notas": "con notas",
        "nroCuenta": "12365478963258741",
        "timeMod": "06102020",
        "tipo": "01",
        "uso": "01",
        "whoMod": "1236528"
    }

```

## `Method POST` /cuentas-bancarias
**Crea o actualiza la información de los datos de una cuenta bancaria**

Crea o actualiza la información de la cuenta bancaria especificada.

**Example Input**

```
	
    {
        "cuentaBancariaId": null,
        "apertura": "2020-10-08",
        "banco": "vz",
        "cierre": "2021-10-08",
        "cuenta": 1236547,
        "cuentaCont": "corriente",
        "dateMod": "2020-10-06",
        "descripcio": "cuenta empresarial",
        "genMovImp": 1,
        "moneda": "us",
        "notas": "con notas",
        "nroCuenta": "12365478963258741",
        "timeMod": "06102020",
        "tipo": "01",
        "uso": "01",
        "whoMod": "1236528"
    }

```

**Example Output**

```
[201 OK]	

```

## `Method DELETE` /cuentas-bancarias/{idCuentaBancaria}
**Elimina un registro de las cuentas bancarias**

Elimina la información la cuenta bancaria especificada

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
