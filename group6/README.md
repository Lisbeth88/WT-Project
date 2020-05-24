# GROUP 6

Demo de un Sistema de Voto Electr�nico Universitario usando TURTLE DB

[Project Brief]

[Link to the presentation]

## Members

- CRUZ OMAR
- LINDAO MARIELLA
- PITA FANNY
- TORRES DANNY


## Problem statement

La presente propuesta se realiza en base a la problem�tica que existe al momento de una consulta popular en una universidad de la Ciudad de Guayaquil, debido a que el estudiante debe presentarse en sitio y tradicionalmente utilizan un sistema de votaci�n basado en papel, el estudiante subraya su opci�n de voto, dobla y deposita la papeleta en una urna y ah� termina su funci�n. El estudiante no tiene forma de verificar que en el escrutinio su voto est� correctamente. Por lo tanto, los estudiantes tienen que confiar en la autoridad de la elecci�n y administradores de sistemas que actuar�n honestamente cuando se publican los resultados de la elecci�n.

## Proposal

Como propuesta presentamos un prototipo de un Sistema de Voto Electr�nico, el cual permitir� que el estudiante realice su voto desde cualquier lugar donde se encuentre, y como ventaja adicional el caso de no tener internet estable, se podr� almacenar el voto OFFLINE de una manera sencilla y segura.

Bien, entonces explico c�mo ser�a el proceso:

Ingresar autentificaci�n: esto conlleva al ingreso del n�mero de c�dula, contrase�a y n�mero de PIN (�ste c�digo llegar� al estudiante como parte de la activaci�n de su participaci�n para el voto). 

Registrar Voto: Una vez que ingrese se mostrar� los datos completos del estudiante y seguido se mostrar� la pregunta de la consulta popular la misma que tendr� cuatro opciones, SI, NO, BLANCO y  NULO,  y dar� Clic en Votar.

Luego se procesar� la informaci�n: en el cual verificar� si existe una conexi�n OFFLINE, por lo que se almacenar� la informaci�n temporalmente en una base interna una vez que se reestablezca la conexi�n mediante un proceso subir� a la base de datos principal.

Y en el caso de que est� ONLINE se almacenar� la informaci�n directamente en la nube.

Finalmente el Administrador tendr� la opci�n de Reporte donde podr� obtener los resultados de la votaci�n.

Tambi�n se contar� como una pol�tica, el Respaldo de la base de datos, por cualquier situaci�n catastr�fica que llegase a pasar.

, que el d�a de la consulta popular, almacenar dicho respaldo con frecuencia cada media hora en otro servidor distinto que estar� ubicado en un centro de datos cercana a la universidad, para garantizar que los respaldos puedan ser usados y est�n disponibles en caso desastres.







Ventajas
1.	Accesibilidad.- ejercer el derecho a votar desde cualquier lugar (casa, trabajo, universidad, etc.). As� como tambi�n favorece el voto a estudiantes en pa�ses extranjeros.
2.	Eficiencia.- Existe ahorro en recursos financieros, no es necesario imprimir papeletas de la elecci�n y los certificados, es decir reduce el consumo de materias primas en papeler�a y urnas de cart�n.
3.	Fiabilidad.- Facilitan el proceso electoral, ya que ofrecen datos fiables. 
4.	Precisi�n.- publicaci�n de resultados r�pidos en cuanto a captaci�n de votos.
5.	Se implementa menor log�stica por parte de los miembros de la fuerza p�blica. 
6.	La carga de trabajo de los funcionarios electorales es liviana, reducen los errores humanos.
7.	El estudiante puede verificar su elecci�n en cualquier momento. 
 Desventajas 
1.	Genera menor cantidad de empleos. 
2.	El hardware y software necesarios para su implementaci�n son elevados, contemplando el costo total de propiedad, a lo que se debe a�adir mantenimiento, licencias, soportes y capacitaci�n. 
3.	Se requieren estar alineados a reformas legislativas. 
4.	Desconfianza del electorado para el uso de los medios electr�nicos en oficios democr�ticos.


## References


- Contenido para usar Aplicaciones Online
[Let's Build an Offline Web App ] (https://www.youtube.com/watch?v=nAIoheQ9iy8)
[Crea_aplicaciones_web_Offline_con_Cache_de_HTML5] (https://xitrus.es/blog/97/Crea_aplicaciones_web_Offline_con_Cache_de_HTML5)
[Prueba de conexion en offline con server worker] (https://www.youtube.com/watch?v=vd_5RwnfX4M) 

- Funcionamiento de voto electronico 
[C�mo funciona el Voto Electr�nico No Presencial] (https://www.youtube.com/watch?v=H7YD6W-fGfc)
[ El voto electr�nico por internet] (https://www.youtube.com/watch?v=dgupZHdsBUo)

- IndexDB 
[Ver y cambiar datos indexados de DB con Chrome DevTools] ( https://developers.google.com/web/tools/chrome-devtools/storage/indexeddb)
[localStorage en HTML5. El fin de las cookies] ( https://rolandocaldas.com/html5/localstorage-en-html5) 
[IndexedDB: Tu base de datos local en HTML5] (https://rolandocaldas.com/html5/indexeddb-tu-base-de-datos-local-en-html5) 
[IndexedDB: Agregando objetos al almac�n] ( https://rolandocaldas.com/html5/indexeddb)
[IndexedDB: Recuperando los datos almacenados] ( https://rolandocaldas.com/html5/indexeddb-recuperando-los-datos-almacenados)  
[Html5: Metodos de almacenamiento en cliente] (http://www.cantabriatic.com/html5-metodos-almacenamiento-cliente/)
[Descripci�n general del almacenamiento web] (https://developers.google.com/web/fundamentals/instant-and-offline/web-storage?hl=es)

- Seguridad en un voto electr�nico
[Seguridad en voto electronico] ( https://web.mat.upc.edu/jorge.villar/esamcid/rep/evot/reportevotingse2.html
[Sistema_de_votacion_electronica_basado_en_criptografia] ( https://rua.ua.es/dspace/bitstream/10045/94728/1/Sistema_de_votacion_electronica_basado_en_criptogr_Fajardo_Juan_Antonio_Jose.pdf

- Cargar archivo JSON a PowerBI
[Exportar indexDB] ( https://www.npmjs.com/package/indexeddb-export-import