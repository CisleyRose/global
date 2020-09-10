---
id: perfiles
title: API Perfiles
sidebar_label: API Perfiles
---

## `Method GET` /getPerfiles
**Consulta el listado de Perfiles**

Obtiene la descripcion de los perfiles creados

**Example Output**


```
[
    {
        "perfilId": 1,
        "rolDescription": "ADMIN",
        "active": true
    },
    {
        "perfilId": 3,
        "rolDescription": "USER",
        "active": true
    }
]

```

## `Method POST` /savePerfil
**Registra perfil**

Crea o actualiza la información del perfil.

**Example Input**

```
	{
        "perfilId": null,
        "rolDescription": "ADMINISTRADOR",
        "active": "true"
    }

```

**Example Output**

```
	{
		"perfilId": 6,
		"rolDescription": "ADMINISTRADOR",
		"active": true
	}

```
## `Method DELETE` /deletePerfil/{idPerfil}
**Elimina Perfil**

Elimina un registro específico por su id

**Example Output**

```
[200 OK]
```
