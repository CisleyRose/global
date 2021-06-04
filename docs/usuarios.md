---
id: usuarios
title: API Usuarios
sidebar_label: API Usuarios
---

## `Method GET` /usuarios
**Consulta el listado de Usuarios**

Obtiene la descripcion de los usuarios creados

**Example Output**


```
[
    {
        "userId": 1,
        "username": "global",
        "usernameFull": "global",
        "password": "$2a$10$2b1AsHTRY1JW860IXm5bKuI3YSFwON9tkdhLSzKHK2weKWOZ9rOqO",
        "phone": 12345600,
        "connectionLast": "2021-06-03T18:49:29.653+00:00",
        "perfilId": 1,
        "active": true
    },
    {
        "userId": 2,
        "username": "yaruby",
        "usernameFull": "yaruby1",
        "password": "$2a$10$2b1AsHTRY1JW860IXm5bKuI3YSFwON9tkdhLSzKHK2weKWOZ9rOqO",
        "phone": 12345600,
        "connectionLast": "2021-05-28T00:00:00.000+00:00",
        "perfilId": 2,
        "active": true
    }
]

```

## `Method GET` /usuarios/usuario/{username}
**Obtiene un usuario especifico por el username indicado**

Obtiene un usuario especifico por el username indicado

**Example Output**


```
	{
		"userId": 2,
		"username": "yaruby",
		"usernameFull": "yaruby1",
		"password": "$2a$10$2b1AsHTRY1JW860IXm5bKuI3YSFwON9tkdhLSzKHK2weKWOZ9rOqO",
		"phone": 12345600,
		"connectionLast": "2021-05-28T00:00:00.000+00:00",
		"perfilId": 2,
		"active": true
	}
```

## `Method GET` /usuarios/{idUsuario}
**Obtiene un usuario especifico según el id indicado**

Obtiene un usuario especifico según el id indicado

**Example Output**


```
	{
        "userId": 2,
        "username": "yaruby",
        "usernameFull": "yaruby1",
        "password": "$2a$10$2b1AsHTRY1JW860IXm5bKuI3YSFwON9tkdhLSzKHK2weKWOZ9rOqO",
        "phone": 12345600,
        "connectionLast": "2021-05-28T00:00:00.000+00:00",
        "perfilId": 2,
        "active": true
    }
```


## `Method POST` /usuarios
**Registra usuario**

Crea o actualiza la información del usuario.

**Example Input**

```
	{
        "userId": null,
        "username": "global4",
        "usernameFull": "globalfull4",
        "password": "$2a$10$2b1AsHTRY1JW860IXm5bKuI3YSFwON9tkdhLSzKHK2weKWOZ9rOqO",
        "phone": 12345600,
        "connectionLast": "2021-05-28",
        "perfilId": 5,
        "active": true
    }

```

**Example Output**

```
[201 OK]
```

## `Method DELETE` /usuarios/{idUsuario}
**Elimina Usuario**

Elimina un registro específico por su id

**Example Output**

```
	{
		"codRespuesta": 200,
		"msgRespuesta": "OK",
		"content": null
	}
```
