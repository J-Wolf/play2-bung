# 
https://gitlab.beyondit.at/martin.schipflinger/klausur_web15_2<br>
https://www.playframework.com/documentation/2.6.x/JavaEbean#Configuring-the-sbt-plugin<br>
1.<br>
Runterladen Scala, XAMPP, sbt und alle unter plugins installieren<br>

2.<br>
build.sbt:<br> 
•	librarydependencies += evolutions<br>
•	ebean enableplugins(,Playbean)<br>
•	webjars over bootstrap (Teil ganz unten)<br>
Project Ordner<br>
plugins.sbt:<br>
•	Plugins einfügen<br>
refresh<br>
in der mainscala.view Datei: fontawsome, bootstrap einbinden (Lange links zum einbinden)<br>
application.conf: <br>
•	Ebean.default.(“models.*“) eckige klammern+<br>
username auf root und passwort auf "" ändern <br>
XAMPP starten<br>
dann http://localhost/phpmyadmin<br>
buchdb erzeugen<br>
Importbefehl für ebean überprüfen sonst nimm den aus der Docu.<br>
3.<br>
Buch:				              Autor:<br>
(at)manytoone			        (at)onetomany(mapped by “autor”)<br>
Private Autor autor;		    privateList<Buch>books;<br>
 

