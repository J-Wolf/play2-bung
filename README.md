# https://gitlab.beyondit.at/martin.schipflinger/klausur_web15_1 
https://gitlab.beyondit.at/martin.schipflinger/klausur_web15_2
1.
Runterladen Scala, XAMPP, sbt und alle unter plugins installieren

2.
build.sbt: 
•	librarydependencies += ecolutions
•	ebean enableplugins(,Playbean)
•	webjars over bootstrap (Teil ganz unten)
Project Ordner
plugins.sbt:
•	Plugins einfügen
refresh
in der mainscala.view Datei: fontawsome, bootstrap einbinden (Lange links zum einbinden)
application.conf: 
•	Ebean.default.(“models,*“) eckige klammern+
Importbefehl für ebean überprüfen sonst nimm den aus der Docu.

Buch:				Autor:
(at)manytoone			(at)onetomany(mapped by “autor”)
Private Autor autor;		privateList<Buch>books;
 

