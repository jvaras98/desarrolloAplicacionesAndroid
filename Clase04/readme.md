Clase 04
---------
Think With Google
Habla acerca de como poder captar la atencion del publico objetivo, como crear experiencias q genern mayor vinculos con los usuarios.. para poder monetizar las aplicaciones.4
Experience & design
Conversiones.- 
principios de buenas practicas para q todas las aplicaciones alcanzen una mayor experiencia.. 

Nos muestra el patron bottom navitaction, un conjunto de opciones en la parte inferior
nuestra intencion final dasboard , entries y settings

CarCare,- me permite q pueda vizualizar mi registro de cmbustible

una propiedad de BottomNavigationView dice Menu, es un recurso del proyecto q esta aqui.
terminamos con la edicion de la "MasterPage"..

el botton Navigation indica que yo puedo establecer un area de visualizacion, y puedo repoblar lo que aparesca en dicha area, por eso las acciones siguen en el activity, 
los 3 elementos son opciones de primer nivel,
vamos a trabajar para q las vistas sean remplazadas en tiempo de ejcucion por cada tab, 

Activity representa todo el area.

Fragment: un subconjunto del area de vizualizacion que puede tener asociado comportamiento, para nuestro caso cada una de las opcioniones implica que el area de visualicacion se apoblada con el contenido de un frag, y cuando se cambia de opcion se va a cambiar el contenido a otro frag en tiempo de ejecuccion.

Recordamos q cada item del navigation view, tiene un ID.. pero tbm sabemos q hemos creado 3 fragments, la primera base logica dekl comportamiento del activity es que en funcion de la logica implementaremos la base para ese comportamiento. 

Android considera esto como una operacion de cambio, ademas adopto la metafora de gestion de base de datos, un conjunto de una o mas operaciones de cambio, es una transaccion, debe ser parte de una.

llenar gasolina
FuelUpEntry: clase q representa a una entrada de registro combustible

Repasar Patrones de Diseño Chain.

En android toda aplicacion q se ejecuta es una instancia de application, tenemos q crear una clase q sea descendiente de la clase aplication.

Super(); llamar al constructor de la clase padre.

ctrl + O : para crear un metodo de una clase override

patron Delegate.- 
creamos una clase descendiente de la clase application, la clase dentro de la aplicacion en cualquier activity solo se puede manejar una instancia de apllication, por que la crea Android, nosotros creamos el contructor pero nunca lo vamos a invokar. lo invoca el SO, es por eso que le hacemos una referencia a ello e introducimos el concepto de SINGLETON, una clase con atributo static de clase no de instancia, lo convierte en un comportamiento a nivel de clase , no a nivel de instancia, quiere decir q dentro del codigo puedo invokar al metodo solamente indicando el nombre de la clase a la q pertenece, y esto, vmos a usarlo de puente
nuestro objeto aplicacion va a obtener una unica instancia de la fuente de datos. 

delegate: el comportamiento de servie esta siendo delegado a la clase carCareApp 


tbm tenemos q decirle a android q cuando uses la clase utilize mi clase application en el manifests

Amdroid reconoce ya la clase creada y la coloca predeterminada

Gerarquia de navegacion

vamos a utilizar TextInputLayout .- componente caracteristico de Material Design, un placeholder que cuando se empiesa a escribir se convierte en etiqueta
la primera propiedad q le pone es un id
las buenas practicas nos indican que no enviemos valores estaticos y ponerlos como recursos String

proxima semana: presentacion de ANDROID
el aula vrtual, version corregida de la primera entrega; 