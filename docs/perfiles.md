---
id: perfiles
title: API Perfiles
sidebar_label: API Perfiles
---

## `Method GET` /perfiles
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

## `Method GET` /perfiles/{idPerfil}
**Obtiene el perfil indicado por el id**

Obtiene el perfil indicado por el id

**Example Output**


```
    {
        "perfilId": 3,
        "rolDescription": "USER",
        "active": true
    }

```

## `Method GET` /perfiles-no-users
**Obtiene los perfiles que no estan asignados a un usuario**

Obtiene los perfiles que no estan asignados a un usuario

**Example Output**


```
[
    {
        "perfilId": 5,
        "rolDescription": "user",
        "active": true
    },
    {
        "perfilId": 7,
        "rolDescription": "Desarrollador",
        "active": false
    }
]

```

## `Method POST` /perfiles
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
[201 OK]
```

## `Method DELETE` /perfiles/{idPerfil}
**Elimina Perfil**

Elimina un registro específico por su id

**Example Output**

```
{
    "codRespuesta": 200,
    "msgRespuesta": "OK",
    "content": null
}
```
