>> Nombre: Bryan Gómez Barrantes
>>
>> Carnet: 2020067440

> ### Índice
>>
>> ###1. [`Introducción y Justificación`](#Introducción y Justificación)
>>
>> ###2.  [`Entidades`](#Entidades)
>>
>> ###3.  [`Atributos`](#Atributos)
>>
>> ###4.  [`Tipos de datos a usar para atributos`](#Tipos de datos a usar para atributos)
>>
>> ###5.  [`Llaves Primarias`](#Llaves Primarias)
>>
>> ###6.  [`Llaves Foráneas`](#Llaves Foráneas)
>>
>> ###7.  [`Índices`](#Índices)

<a name="Introducción y Justificación"> </a>

> ### Introducción
>> El esquema de nombres presentado a continuación, hace uso de las mayúsculas al inicio de una palabra y en otros casos
> hace uso de estas en toda la palabra,teniendo así una mayor facilidad para encontrar y manejar las entidades,
> atributos, tipos de datos en atributos, llaves primarias, llaves foráneas e índices, todo dependiendo del dato que se
> busque. 

> ### Justificación
>> Este esquema tiene la finalidad de dar una legibilidad más cómoda al usuario, haciendo que los datos sean un poco más
> manejables y fáciles de encontrar, ya que cada uno al tener un formato, se vuelve más simple hacer uso de estos.

<a name="Entidades"> </a>

> ### Entidades
>> En el caso de las entidades ópte por utilizar un formato con la primera letra
> mayúscula y las siguientes minúsculas

 #### Ejemplos:
 
- create table Estudiantes();
- create table Organizaciones();
- create table Empresas();
 
####Excepciones
En el caso de que la entidad posea 2 o más palabras, se útiliza un guión bajo y minúsculas:
- create table Estudiantes_reprobados();
- create table Organizaciones_excluídas();
- create table Empresas_internacionales();

<a name="Atributos"> </a>

> ### Atributos
>> Para los atributos se tendría una forma similar a la de entidades, ya que de igual manera empezarían con su
> primera letra mayúscula y las demás minúsculas.

####Ejemplos:

create table Estudiantes(
>Nombre varchar(30),
> 
>Apellido varchar (30)
> 
); 



####Excepciones
En el caso de que el atributo posea 2 o más palabras, se útiliza un guión bajo y minúsculas:

create table Estudiantes(
>Nombre varchar(30),
>
>Apellido varchar(30)
> 
>Segundo_apellido(30)
>
);

<a name="Tipos de datos a usar para atributos"> </a>

> ### Tipos de datos a usar para atributos
>> En el caso de los tipos de datos se estaría utilizando toda la palabra en minúscula. En este apartado no se
> encuentran excepciones.
>
####Ejemplos:

create table Estudiantes(
>Nombre varchar(30),
>
>Apellido varchar(30)
>
>Segundo_apellido(30)
>
);
<a name="Llaves Primarias"> </a>

> ### Llaves Primarias
>> En el caso de llaves primarias se utilizarían las letras en mayúscula en toda la palabra.

####Ejemplos:

create table Estudiantes(
>CARNET int primary key auto_increment,
> 
>Nombre varchar(30),
>
>Apellido varchar(30)
>
>Segundo_apellido(30)
>
);
<a name="Llaves Foráneas"> </a>

> ### Llaves Foráneas
>> 

<a name="Índices"> </a>

> ### Índices
>> 