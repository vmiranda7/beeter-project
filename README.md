Ejercicio 1 Beeter API. Trabajo en casa

1. Implementar la realización de búsquedas en los campos subject y content de los
stings en la URI relativa:
/stings/search?subject={subject}&content={content}&length={length}
donde length corresponde al número máximo de registros que puede devolver la
búsqueda.
(Se encuentra en STINGS RESOURCE)

2. Implementar los siguientes nuevos requisitos del servicio Beeter:

- Todos los usuarios registrados pueden acceder al perfil cualquier usuario que
debe poder ser cacheado.
(Se encuentra en USUARIOS RESOURCE)

- Cualquier usuario puede modificar y borrar su perfil aunque no se borrarán los
stings que él haya creado.
(No puedes eliminar un usuario sin eliminar todos sus stings)

- Se debe poder acceder a una colección de todos los stings creados por un
determinado usuario. La colección debe poderse paginar y la URI no debe
utilizar un query parameter para discernir el usuario.
(Se encuentra en STINGS RESOURCE)


# Beeter

Beeter is an educational project developed at course "Design of Services and Applications" of  Castelldefels School of Telecommunications and Aerospace Engineering (EETAC). Beeter is a very simple microblogging service with a web front-end developed with Bootstrap and jQuery, and an android front-end.

## System requirements
To install Beeter you must have installed:

- JDK 7.0
- Maven
- Tomcat
- Apache
- MySQL

## Installation

Clone this project and follow the instructions of each one of the individual subprojects:

- sql
- www
- beeter-server
- beeter-android
