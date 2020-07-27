---
id: usuarios
title: API Usuarios
sidebar_label: API Usuarios
---

## `Method GET` /getUsuarios
**Consulta el listado de Usuarios**

Obtiene la descripcion de los usuarios creados

**Example Output**


```
[
    {
        "userId": 1,
        "username": "Prueba",
        "usernameFull": "Prueba Global",
        "password": "$2a$10$MPcBLMO.6NPGB1DwVcn7NuypqXy7MZECQmf5Zd3HOAzn1EfmajZx.",
        "phone": 5689568745411,
        "connectionLast": "2020-07-22T00:00:00.000+00:00",
        "perfil": {
            "perfilId": 1,
            "rolDescription": "USER",
            "active": true
        },
        "active": true
    },
	{
        "userId": 2,
        "username": "Prueba2",
        "usernameFull": "Prueba Global",
        "password": "$2a$10$MPcBLMO.6NPGB1DwVcn7NuypqXy7MZECQmf5Zd3HOAzn1EfmajZx.",
        "phone": 5689568745411,
        "connectionLast": "2020-07-22T00:00:00.000+00:00",
        "perfil": {
            "perfilId": 2,
            "rolDescription": "ADMIN",
            "active": true
        },
        "active": true
    }
]

```

## `Method POST` /saveUsuario
**Registra usuario**

Crea o actualiza la información del usuario.

**Example Input**

```
	{
        "userId": null,
        "username": "Global",
        "usernameFull": "Prueba Global",
        "password": "12345",
        "phone": "5689568745411",
        "connectionLast": "2020-07-22T00:00:00.000+00:00",
        "perfil": {
            "perfilId": 5,
            "rolDescription": "ADMINISTRADOR",
            "active": true
        },
        "active": true
    }

```

**Example Output**

```
	{
		"userId": 11,
		"username": "Global2",
		"usernameFull": "Prueba Global",
		"password": "$2a$10$0YP6vHWYpHLPan3LQBEG5epQGuvk/R6LNSHuw3mwaZjLrSsX.Gmvm",
		"phone": 5689568745411,
		"connectionLast": "2020-07-22T00:00:00.000+00:00",
		"perfil": {
			"perfilId": 6,
			"rolDescription": "administrador",
			"active": true
		},
		"active": true
    }

```
## `Method DELETE` /deleteUsuario/{idUsuario}
**Elimina Usuario**

Elimina un registro específico por su id

**Example Output**

```
[200 OK]
```
