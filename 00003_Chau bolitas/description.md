Como adelantamos en la descripción de la guía, todo nuestro **dominio** lo vamos a representar con bolitas de distintos colores. Lo primero que vamos a querer representar es cuántos estudiantes hay en cada escuela y, para ello, vamos a usar bolitas azules (una por estudiante).

Si bien podríamos usar directamente `Azul` cada vez que queramos hablar de estudiantes, eso tiene algunos problemas: 

1. no es para nada obvio que `Azul` quiere decir estudiantes, y eso hace que nuestro programa sea más difícil de comprender;
2. si en algún momento queremos cambiar el `Azul` por otro color, hay que buscar **todos** los lugares donde diga `Azul` y cambiarlo;
3. nos cuesta mucho más "despegarnos" del tablero porque seguimos expresando nuestro problema en términos de bolitas.

> Por todo esto, te vamos a pedir entonces que definas las siguientes funciones:
>
> * `colorEstudiantes()`, que denote el color `Azul` (sí, así de sencilla como te la imaginás);
> * `cantidadEstudiantes()`, que utilice la anterior y nos diga cuántos estudiantes hay en la celda actual.