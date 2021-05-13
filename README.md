# Unit-files
Dieses Repository enthält die innerhalb der zweiten Phase des Studienprojektes erstellten Unit-files.

## update-database.service
Diese Service Datei dient der automatischen Aktualisierung der Fahrzeugdatenbank. Dabei wird diese Datei ausgeführt, sobald der Rapsberry Pi, welcher als Server verwendet wird, eine Internetverbindung hergestellt hat. Daraufhin ruft die Service Datei ein Python-Programm auf, welches die [csv-Datei mit den hinzuzufügenden Fahrzeugen](https://github.com/DHBW-Studienarbeit-Fahrzeug-Datenlogger/Studienarbeit_OBD_Datenlogger/blob/main/MySQL-server/cars_update.csv) herunterlädt und diejenigen Fahrzeuge in die Datenbank hinzufügt, welche nicht bereits in dieser bestehen.
