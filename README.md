# Dream Team

### ¿Que es Dream Team?
Dream Team es una aplicación free to use que pretende facilitar generar equipos de futbol para ti y tus amigos.
A diferencia de otras aplicaciones que el parametro que utilizan para dividiros es "vuestro nombre" ( entre comillas porque es generado aleatoriamente), Dream Team tiene en cuenta las habilidades de los participantes del partido y genera el emparejamiento matematicamente mas equilibrado 👍🏼

¡Cuanto más uses Dream Team para tus pachangas, mejores seran los encuentros! ¿Y como es eso te preguntaras? Bueno la respuesta es bastante más sencilla de lo que parece.

Cuando creamos la liga tendremos que añadir a nuestros amigos a ella dandole una puntuacion inicial a cada uno en los siguientes aspectos : `Tiro` `Centro` `Defensa`. El programa generara su primera media en base a estos 3 parametros. Cuando termineis el partido que has creado, deberas puntuar a tus amigos en estos mismos aspectos. Gracias a esto Dream Team siempre podra crear los emparejamientos mas justos y equilibrados para que vuestros partidos sigan siendo emocionantes

¡Aparte podreis ver vuestro desarrollo individual graficamente!

Tambien somos conscientes de que el futbol no es lo mismo sin espectadores, asique nuestra aplicacion cuenta con un modo espectador. Lo unico que tendras que hacer es compartir el código de la liga con vuestros amigos y podran ver el avance de la liga

A continuación entraremos un poco mas en detalle en cada uno de las partes de las que esta compuesta el proyecto

Si tienes interes en ver como se ve la aplicación, en el apartado de Ionic tendras algunas capturas 😋

En la version actual del proyecto nos encontramos con las siguientes partes
| x | Ionic | Angular | Api REST |Static Web
|--|:--:|:--:|:--:|--|
| Enlaces |  Ionic | Angular | Api REST | Static Web
| Version | `13.2.6` | `13.1.4` | `Python 3.9.13` |
| Librerias | Ng-charts | Angular Material y Primeng | Fast api y pyrebase

## Ionic

La aplicacion en ionic, tiene toda su lógica externalizada en la Api Rest, haciendola muy rapida y poco pesada
| x |Correo |Contraseña |
|--|--|--|
| | `prueba@gmail.com` | `123456` |

Se recomienda usar las credenciales de arriba para poder probar la apliación y a  ser posible entrar en la liga `Prueba2`, ya que es la que tiene algunos datos dentro

La aplicación es dependiente de la Api REST
| x |Modelos|Vistas| Servicios | Páguinas | Componentes
|:--:|:--:|:--:|:--:|:--:|:--:|
| | `7` | `2` | `4` | `4` | `5`

Mapa de navegación

Capturas

## Angular

En angular podremos encontrar una pequeña vista de admin que nos permite ver a todos los jugadores de todas las ligas y ver en unas graficas para ver su desempeño. Su valor es analitico, ya que permite una vista rapida, sencilla y compacta de la información de la aplicación

Capturas

## Api Rest con Fast Api

El cerebro pensante de la aplicación. Esta parte gestiona toda la lógica y las consultas a la base de datos ( Fire Base )

A continuación se listan sus 12 endpoints. Para una explicación más en profundidad de los parametros que tienen que ser mandados, pongase en contacto conmigo

| Tipo | Url |
|:--:|:--:|:--:|
| Post | `/registerUser` |
| Post | `/get` |
| Post | `/createLeague` |
| Post | `/spectateLeague` |
| Post | `/getLeagues` | 
| Post | `/createPlayer` |
| Post | `/getPlayers` |
| Get | `/getAllPlayers` |
| Post | `/createMatch` |
| Post | `/getMatches` |
| Post | `/endMatch` |

## Static - Web

Capturas

