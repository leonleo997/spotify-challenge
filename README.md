# Spotify Challenge  

Spotify lo ha contratado a usted para realizar pruebas a la API que ellos suministran debido a que han modificado dos de los servicos más importantes en su negocio.  

El primer servicio se encarga de generar la autenticación que generará un access token que es fundamental para utilizar los demás servicios de la API. Es importante validar que la petición haya respondido correctamente ya que con ello, el front sabrá que el proceso fue exitoso, y validar que entre su respuesta se encuentre un access token.

El segundo se encarga de hacer una búsqueda ya sea por album, canción, artista, etc. Este servicio es uno de los más críticos para el negocio debido a que es donde los usuarios más navegan. Además, se quiere que la petición se haya hecho correctamentamente, y también, se desea hacer una petición a este servicio donde se verifique que al consultar la canción "Till I Collapse" se retorne 20 tracks. 

## Requisitos  

Usted debe mandar al menos tres pull request: El primero con el setup del proyecto, el segundo con la prueba para la autenticación, y el último, con una prueba para la búsqueda de la canción. RECUERDE puede hacer más Pull Requests.  

## Cheat  

Para generar la autenticación debe tener un CLIENT_ID y un CLIENT_SECRET. Para esto, recuerde estar registrado en Spotify e ir al dashboard de https://developer.spotify.com/.

Además, es muy importante que usted aplique **las mejores prácticas** a la hora de desarrollar el challenge  :D
