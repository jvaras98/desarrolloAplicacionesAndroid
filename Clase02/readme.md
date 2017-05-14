Entregable :
https://utpedupe-my.sharepoint.com/personal/u17107289_utp_edu_pe/Documents/Forms/All.aspx?RootFolder=%2Fpersonal%2Fu17107289_utp_edu_pe%2FDocuments%2F2017%20-%202%2FAndroid%20business%20application%20developement&FolderCTID=0x01200062C3AD0807972A46A20462141CFF350C

Inicio:
recomendaciones.-
el lenguaje q se apoya el android es java, aqui las biblioteca 
se conocen como paquetes, estas tienen una nomenchatura,, DNS invertido.. 
convecion ejempo "pe.edu.utp"

android se apoya en el home del usuario por eso se crea un AndroidStudioProjects
y luego crea una caprpeta con el mismo nombre del proyecto

2da vista:
eleccion de nivel de API base para la aplicacion. 

opcion help me choose:
en esta vista se aprecia qe para cada version el numeros, participacion en el parque de dispositivos
a nivel acumulado
ejemplo : API 22 es el 24% de dispositivos 
API 19 es el 73% de dispositivos
mientras menos level restringe muchas funcionalidades 

3ra vista: 
cual es el tipo de exqperiencia aquirimremos par el proyecto

4ta vista:
nombre de proyecto

click finish.
:
Activity: una experiencia mobile para android estan constituidas por una o mas actividades, un foco de interacion entre la aplicacion y el usuario
esta compuesto por 2 partes importantes_:
comportamiento: alojado en una clase de java
estructura de interfas : esta espefificada en un archivo xml (de layout)

proposito Tipo de clase
Activity Name: como se va a llamar tu clase, respetando el camelCase

tipo de contenido / y el proposito que debe ser un match co nla clase de jama
Layout Name : nomenclatura en minuscula y se separa con "_", 

tipo de cotendio _ / proposito
Archivo de recurso : tbm es un archivo xml

Contenido (estructura):
-----------------------
Gestores de dependencias
Gradle Scripts

Projecto; conjunto de 1 o mas modulos,
primer modulo app

archivo mas importante : AndroidManifest.xml (biblia de proyecto). medio de comunicacion entre la 
aplicacion y el ordenador.

supportRTL: Right to Left
en la cultura occidental normalmente se lee de izquiera a derecha, 
pero otras culturas es de derecha a izquirda.
por eso es q la aplicacion se puede adaptar a la cultura en la que
se utiliza.

una aplicacion puede contener muchas etiquetas activitis

itent-filter: le indican al sistema operativo q este es el principal activity
algo asi como javaweb. con files

el activity: esta compuesto por un clase de java y un archivo de layout

/* App*/
public class MainActivity extends AppCompatActivity {
}

AppCompatActivity: es el nombre de una clase q viene con android

los activitys tienen un ciclo de vida, al igual q los servlet
onCreate se ejecuta cuando recien se instancia del activity, onDestroy

setContentView(R.layout.activity_main); 
establece el vinculo con el layout, R-> es un alias q representa app/res
q es resources (recursos de la aplicacion)

Drawable: dibujos, imagenes
layout 	: 
menu 	:
mipmap 	: imangenes binarias
Values 	: 

Toolbar toolbar = (Toolbar)findViewById(R.id.toolbar); 
/*encuentra la vista por id*/

<android.support.design.widget.CoordinatorLayout /*tipo de clase*/
layout_width : ancho "match_parent(ocupar todo el ancho del area q la contenga)"
layout_height : largo igual arriba
context; 

android.support.design.widget.AppBarLayout : la barra desplegable

android.support.v7.widget.Toolbar()
android:id="@+id/toolbar" aqui esta el id


android.support.design.widget.FloatingActionButton :
filosofia de diseño
google matiller design: aplica para interfaces web, moviles, y televisores
apple human interface guidelines 
Microsoft bill 2017 ; desde el 10 a 12 de mayo (evento de tecnologia)
en este envento lanzo la neuva filosofia de diseño
microsoft plgin design sytstems-> orientada a cubrir multiples diseños , desktop, mobile win apple android
werawell, realidad virtual 
>>>>>>>>>>> 17 de mayo (google IO) <<<<<<<<


wrap_content : se ajusta al tamaño del contenido:
gravity: la fuerza con la q jala a los elemento

alias :
android:layout_gravity="bottom|end"
start : izquierda
end : derecha

app:srcCompat="@android:drawable/ic_dialog_email" />

FloatingActionButton fab = (FloatingActionButton) findViewById(R.id.fab);
instancia q hace referencia al floating button

setOnClickListener .-> se refiere al tab
principios de POO , lo q necesita es u n objeto de la clase 

Snackbar : de la parte inferior surge una area de un mensaje

no  abre porq esta desabilitado el VT-x

si no aárece el boton rojo 
File/Setting/plugins

NeedFinding

Entrevistas-> User POersonas personas 

user persona->
user task matrix->
user journey map -> procesos, pensamientos q atacan a las personas 
en cada instancia

user stories: como el rol dese de feature para el beneficio
los criteros de aceptacion : condiciones q deben cumplirse para q el user stories st completo

wirewrames : anotaciones.. en lucidCHART

referencias :
uxpin
otis cole UX design: es una agencia
http://otiscole.com/
ejemplo de toda esta mierda dicha arriba esta aqui
Whats Cokiee

para user stories 
http://www.seguetech.com/ebooks/
"Adopting Agile Development"

Autonomo:
Material design para aplicaciones android 
contexto: introduccion a la calidad de diseño
y guia para almenos 3 componentes 
excluyan textview, etiquetas o botones standares
componentes q vienen con la filosofia material design

Proxima semana:
nombre del producto
objetivos , alcanse, caracteristicas , proceso de needfinding

