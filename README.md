# TP-1

## Tareas

- [ ] Aceptar el assignment y clonar el repositorio con el ejercicio
- [ ] Reemplazar la lista de integrantes con los nombres de los integrantes del equipo en el archivo README.md

## Integrantes

**Equipo:**  Team Rocket

- Ayelen Garcia (@ayelenMacarena)
- Federico Romero (@fecheromero)
- Juan Fernandes (@juanFdS)

## Pre-requisitos

Tener instalado [prolog](https://github.com/pdep-utn/enunciados-miercoles-noche/blob/master/pages/prolog/entorno.md).

## El enunciado

Escribir los tests que consideren importantes en cada punto.

## Punto 1: empleados

Una empresa está buscando candidatos para varios de sus sectores. Se sabe que:

- Roque es contador, honesto y joven.
- Ana es ingeniera y honesta, pero no es joven.
- Cecilia es abogada.

a) Escribí una base de conocimiento que permita consultarla de la siguiente forma:

```prolog
? honesto(ana).
yes
```

Ahora queremos saber qué empleados pueden servir para un sector dado.

Sabiendo que la base de conocimiento contiene hechos de la forma:

- `contador/1`, `honesto/1`, `ambicioso/1`
- `trabajoEn/2`: nos dice si un empleado trabajó antes en cierto lugar. 

b) Desarrollá un predicado `puedeAndar/2` que relaciona a un sector con un empleado si este puede trabajar allí. Considerar que:

- en contaduria solo pueden trabajar contadores honestos
- en ventas solo pueden trabajar ambiciosos que tienen experiencia (gente que haya trabajado en algun lugar antes)
- y lucia siempre puede trabajar en ventas 




## Punto 2: el asesinato de Tia Agatha

Para este punto, no es necesario que escriban tests sobre quien es el asesino (sí sobre a quien odiaría c/u), dejemos que el programa lo descubra por nosotros :).

Escribí un programa Prolog que resuelva el siguiente problema lógico:

- Un asesino siempre odia a su víctima y nunca es más rico que ella. El asesino de la tía Agatha, además, vive en la mansión Dreadbury.
- Tía Agatha, el carnicero y Charles son las únicas personas que viven en la mansion.
- Charles odia a todas las personas de la mansión que no son odiadas por la tía Agatha.
- Agatha odia a todos los que viven en la mansión, excepto al carnicero.
- Quien no es odiado por el carnicero y vive en la mansión, es más rico que tía Agatha
- El carnicero odia a las mismas personas que odia tía Agatha. 

Al programa le tengo que poder preguntar quién es el asesino de la tía Agatha, y tiene que brindar una sola respuesta, de la siguiente forma:

```prolog
? asesino(agatha, Asesino).
Asesino = ???
```

**Nota:** No agregues información que no se provea en el enunciado. Al asumir ciertas cosas que no se explicitan podés llegar a un resultado distinto del esperado.

## Que hacer cuando terminan el TP

Cuando terminen, creen un issue etiquetando a sus tutores así les llega una notificación y se corrigen y les dejan feedback ahí.
![](https://i.imgur.com/ypeXpBw.gif)
