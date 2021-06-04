---
id: modoPago
title: API Modos de Pago
sidebar_label: API Modos de Pago
---

## `Method GET` /modos-pago
**Obtiene el listado de modos de pagos**

Obtiene la información de los modos de pagos existentes en la empresa

**Example Output**


```
[
    {
        "modoPagoId": 1,
        "cuenta": 1,
        "descripcio": "international",
        "docasoc": "doc",
        "fechaDoc": "2021-05-28T00:00:00.000+00:00",
        "formaPago": "tm",
        "monto": 200.0,
        "numDoc": "158745",
        "origenDoc": "90",
        "tipoDep": 1,
        "motivo": "compras",
        "beneficiar": "global",
        "cancc": 15,
        "chequera": 1,
        "factura": 15874,
        "retBase": 145,
        "retConcep": "1",
        "retSustrae": 8,
        "retTasa": 96
    },
    {
        "modoPagoId": 3,
        "cuenta": 1,
        "descripcio": "international",
        "docasoc": "doc",
        "fechaDoc": "2021-05-28T00:00:00.000+00:00",
        "formaPago": "tm",
        "monto": 200.0,
        "numDoc": "158745",
        "origenDoc": "90",
        "tipoDep": 1,
        "motivo": "compras",
        "beneficiar": "global",
        "cancc": 15,
        "chequera": 1,
        "factura": 15874,
        "retBase": 145,
        "retConcep": "1",
        "retSustrae": 8,
        "retTasa": 96
    }
]
```

## `Method GET` /modos-pago/{idModoPago}
**Obtiene un modo de pago especifico según el id indicado**

Obtiene un modo de pago especifico según el id indicado

**Example Output**


```
    {
        "modoPagoId": 1,
        "cuenta": 1,
        "descripcio": "international",
        "docasoc": "doc",
        "fechaDoc": "2021-05-28T00:00:00.000+00:00",
        "formaPago": "tm",
        "monto": 200.0,
        "numDoc": "158745",
        "origenDoc": "90",
        "tipoDep": 1,
        "motivo": "compras",
        "beneficiar": "global",
        "cancc": 15,
        "chequera": 1,
        "factura": 15874,
        "retBase": 145,
        "retConcep": "1",
        "retSustrae": 8,
        "retTasa": 96
    }
```

## `Method POST` /modos-pago
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
[201 OK]
```

## `Method DELETE` /modos-pago/{idModoPago}
**Elimina un registro de los modos de pagos**

Elimina la información del modo de pago indicado

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
