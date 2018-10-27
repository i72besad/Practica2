### Gestión de líderes

**ID:** 006

**Breve Descripción:** El sistema añadira o cambiara a un lider de equipo.

**Actores Principales:** Profesor

**Actores Secundarios:** Alumnos

**Precondiciones:** 

1. Debe de existir el equipo.

2. Debe existir el alumno que va a ser líder.

**Flujo Principal:**

1. El caso de uso comienza cuando el sistema necesita gestionar al líder de un equipo.

2. El sistema añade un nuevo líder a un equipo.

**Postcondiciones:**

* El sistema realiza la copia de seguridad de forma manual (por el usuario) o de forma automática.

**Flujos Alternativos:**

2.1	Si no hay lider de equipo añade directamente al alumno.

2.2 Si existe un líder en ese equipo se le quita la posicion de líder y se añade al nuevo como líder de ese equipo.