# 
https://gitlab.beyondit.at/martin.schipflinger/klausur_web15_2
1.
Runterladen Scala, XAMPP, sbt und alle unter plugins installieren

2.
build.sbt:<br> 
•	librarydependencies += ecolutions<br>
•	ebean enableplugins(,Playbean)<br>
•	webjars over bootstrap (Teil ganz unten)<br>
Project Ordner<br>
plugins.sbt:<br>
•	Plugins einfügen<br>
refresh<br>
in der mainscala.view Datei: fontawsome, bootstrap einbinden (Lange links zum einbinden)<br>
application.conf: <br>
•	Ebean.default.(“models,*“) eckige klammern+<br>
Importbefehl für ebean überprüfen sonst nimm den aus der Docu.<br>

Buch:				              Autor:<br>
(at)manytoone			        (at)onetomany(mapped by “autor”)<br>
Private Autor autor;		    privateList<Buch>books;<br>
 

