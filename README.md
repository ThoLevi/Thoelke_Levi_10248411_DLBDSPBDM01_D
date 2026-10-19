# Thoelke_Levi_10248411_DLBDSPBDM01_D
Portfolio-Projekt im Kurs DLBDSPBDM01_D (Data-Mart-Erstellung in SQL) an der IU Internationale Hochschule

Levi Thölke · Matrikelnummer 10248411
GitHub-Repository: https://github.com/ThoLevi/Thoelke_Levi_10248411_DLBDSPBDM01_D.git
Die Datenbank bildet eine App ab, in der Benutzende Bücher in der Nachbarschaft verleihen und ausleihen. Sie besteht aus 20 Tabellen und läuft auf Microsoft SQL Server 2022.
Dateien
`Thoelke-Levi_10248411_DLBDSPBDM01_D_Finalisierungsphase_SQL_Installation.sql`: führt alle Skripte in der richtigen Reihenfolge aus
`Thölke-Levi_10248411_DLBDSPBDM01_D_Erarbeitungs-Reflexionsphase_SQL_buecher_ausleihe_db.sql`: legt die Datenbank mit allen Tabellen an
`Thölke-Levi_10248411_DLBDSPBDM01_D_Erarbeitungs-Reflexionsphase_SQL_beispieldaten.sql`: fügt Beispieldaten ein
`Thölke-Levi_10248411_DLBDSPBDM01_D_Erarbeitungs-Reflexionsphase_SQL_testfaelle.sql`: ein Testfall je Tabelle
`Thölke-Levi_10248411_DLBDSPBDM01_D_Erarbeitungs-Reflexionsphase_SQL_metadaten.sql`: Anzahl der Tabellen, Einträge und Größe der Datenbank
Installation
Voraussetzung: SQL Server 2022 und SQL Server Management Studio (SSMS).
Alle SQL-Dateien in einen Ordner legen.
`Thoelke-Levi_10248411_DLBDSPBDM01_D_Finalisierungsphase_SQL_Installation.sql` in SSMS öffnen.
Im Menü Abfrage > SQLCMD-Modus aktivieren.
In der Zeile `:setvar SkriptPfad` den Pfad zu diesem Ordner eintragen.
Mit F5 ausführen.
Danach ist die Datenbank mit Beispieldaten angelegt, und im Ergebnisfenster stehen die Testfälle, die Umkreissuche und die Metadaten.
