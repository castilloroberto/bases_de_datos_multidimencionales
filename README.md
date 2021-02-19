# Bases de Datos Multidimencionales

## ETL Extract, transform and load 
Extraer, transformar y cargar
## 04/02/2021
servidor de correos de gogle 
> smtp.gmail.com

## Comando para ejecutar *JOB* desde terminal 

```bash
.\Kitchen.bat -file="direccion del archivo .kjb" -level=Minimal >> direccion de el archivo donde se desea tener el registrolog.txt
```

```bash
.\Kitchen.bat -file="data-warehouse/master_job.kjb" -level=Minimal >> C:\Data_integration\data-warehouse\log.txt
```
## 05/02/2021

## Funciones
```javascript
function cuadrado(x){
    return x * x 
}
```
## Funciones Matematicas
> f(x) = x * x

Donde x es cualquier valor que se nos ocurra
> f(4) = 4 * 4
> y = 16
Decimos que esta funcion retorna 16

1. realizar investigacion
- como se crea una tarea programada en windows como configurarla
- que puede o que lleva un archivo .bat
- Como automatizar la ejecucion de jobs
- crear un archivo .bat para ejecutar el job
- crear una tarea programada en windows que ejecute el archivo .bat ( lo ejecute una vez al dia a la hora de cierre de la empresa x)
- x: 8:00 PM 
- nombre de la tarea: poblar datawarehouse. 
2. Dimenciones:
- Productos
- sucursales
- tiempo pasos (generate rows)
- what is this: producto cartesiano 
3. las dimenciones de un cubo tienen categorias

## Examen Primer Parcial
1. direrencias entre bases de datos relacionales y Dimencionales
- Buscan reducir la redondancia
2. Elemento de un cubo
- Hechos que forman el cubo al ruzar una linea del cubo
3. Step a usar en lugar del dummy
- Correo electronico al producirse un error
4. Fuente de datos para poblar datawarehouse
- cualquiera (bases de datos, hojas de excel)
5. desventaja de usar exel para datawarehouse.
- No tiene muchas herramientas de ETL.
6. Que tiene mas importancia en la creacion de un DataWareHouse
- El diseño que tendra

## Pasos Para Crear un Cubo OLAP
* Primer Paso


## Analisis y Diseño 

### Reporteria 
1. impresion: desventaja costo

2. consideracion para el diseño de reportes:
- Encabezado o titulo del reporte
- numero de paginas
- fecha de creacion del documento (puede llevar dos fechas, de cuando son los datos y cuando se imprimio)
- titulo de columna:  
3. Consideraciones esteticas 
- Diferencias titulos y subtitulos
