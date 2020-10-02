---
id: modoPago
title: API Modos de Pago
sidebar_label: API Modos de Pago
---

## `Method GET` /getmodoPagoList
**Obtiene el listado de modos de pagos**

Obtiene la información de los modos de pagos existentes en la empresa

**Example Output**


```
[
    {
        "modoPagoId": 1,
        "cuenta": "1234567895",
        "descripcio": "prueba",
        "docasoc": "documento",
        "fechaDoc": "2020-10-02T00:00:00.000+00:00",
        "formaPago": "2",
        "monto": "200000",
        "numDoc": "2",
        "origenDoc": "2",
        "tipoDep": "1",
        "motivo": "compra",
        "beneficiar": "global",
        "cancc": "1",
        "chequera": "0",
        "factura": "factura1",
        "retBase": "159632",
        "retConcep": "compra",
        "retSustrae": "1",
        "retTasa": "12"
    }
]
```

## `Method POST` /saveModoPago
**Crea o actualiza la información del modo de pago**

Crea o actualiza la información del modo de pago especificado.

**Example Input**

```
	
     {
        "modoPagoId": null,
        "cuenta": "1234567895",
        "descripcio": "prueba",
        "docasoc": "documento",
        "fechaDoc": "2020-10-02",
        "formaPago": "2",
        "monto": "200000",
        "numDoc": "2",
        "origenDoc": "2",
        "tipoDep": "1",
        "motivo": "compra",
        "beneficiar": "global",
        "cancc": "1",
        "chequera": "0",
        "factura": "factura1",
        "retBase": "159632",
        "retConcep": "compra",
        "retSustrae": "1",
        "retTasa": "12"
    }

```

**Example Output**

```
	{
		"modoPagoId": 5,
		"cuenta": "1234567895",
		"descripcio": "prueba",
		"docasoc": "documento",
		"fechaDoc": "2020-10-02T00:00:00.000+00:00",
		"formaPago": "2",
		"monto": "200000",
		"numDoc": "2",
		"origenDoc": "2",
		"tipoDep": "1",
		"motivo": "compra",
		"beneficiar": "global",
		"cancc": "1",
		"chequera": "0",
		"factura": "factura1",
		"retBase": "159632",
		"retConcep": "compra",
		"retSustrae": "1",
		"retTasa": "12"
	}

```
## `Method DELETE` /deleteModoPago/{idModoPago}
**Elimina un registro de los modos de pagos**

Elimina la información del modo de pago indicado

**Example Output**

```
[200 OK]
```
