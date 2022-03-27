
# Introducción

Un sistema operativo es un programa que se encarga de ser la interfaz[^1] entre el usuario y el hardware de la maquina. Para lograrlo tiene varias funciones:

1. Control de dispositvos;  El SO a traves drivers[^2] se conecta a los dispositivos con el *I/O Controller* como responsable para controlar sus acciones.
2. Control de la memoria; En este apartado nos referimos a la memoria RAM, la memoria de acceso rápido
3. Control de procesosos: En casos cuando hay concurrencia el SO decide que proceso será ejecutado, decide a que proceso se le prestara tiempo de ejecución del procesador.
4. Control de archivos: Controla lo que hay en la memoria principal permanente, como acceder a ella.

Otros aspectos que controla son, seguridad, coordinación, manejo de errores(como servicio).

Los sistemas operativos de tipo *Batch* son aquellos que reciben paquetes de programas para ser ejecutados y no tienen contacto directo con el usuario, toma en el batch los datos
y el programa y los lanza a ejecución en orden.

*¿Son los de tarjetas perforadas o hay más?

*por otra parte los
de tiempo compartido son los que utilizan un mismo cpu para un mismo usuario y usan el concepto de concurrencia.

*¿Los sistemas de red y tiempo real son diferentes a los usuales?
*Los sistemas real-time son como cualquier so con caracteristicas especiales

[^1]:[Definición precisa]()
[^2]: [Programas del programa central]()
* Programa minimo


## Propiedades
- Spooling, es la propiedad de mantener información en el buffer para el multitasking


## Procesos

- La definición de un proceso y sus partes, con una comparación con un programa
- La definición del PCB como estructura de datos que tiene el SO para organizar los procesos


Procces scheduling.
- Tenemos los estados de un proceso y cada estado tiene su propia cola de espera.
- We have 3 schedulers long term, medium term, short term
	- short term changes from execution to wait and wait to ready?
- context switch es un mecanismo
- el lugar donde guarda la información para su uso posterior es el PCB, y ¿es la misma información?


- Medium term scheduler no se tiene en VM Cardiac
# Dudas
- ¿Cuales son los dispositivos? Aquellos externos al funcionamiento de la computadora, en este apartado no se considera como dispositvos al cpu o memoria ram.
- multiprogramming
- ¿Distributed systems son sustituidos por hadoop?
- ¿Que es un servicio?
- ¿que es un mecanismo a diferencia de un programa?

# DUdas con mini SO

- no funciona el multitask, cuando esta en espera un proceso no se ejecuta otro

# Ideas

- Separar los elementos del SO implementado con la maquina concurrente para que sea posible crear un SO en esa maquina o quiza más de uno si a alguien se le ocurre
- posibilidad de borrar el sistema operativo para cargar otro
