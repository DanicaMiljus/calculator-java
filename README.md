LOC za kopletan projekat iznosi 214

Fajl. Calkulator.java
LOC=188
Ciklomatska slozenost za evaluateExpression = 12 (umeren rizik)
                         Calculate = 12 ( umeren rizik )
Kognitivna slozenost za  evaluateExpression = 9
                         Calculate = 13
Fajl. Start.java
LOC=26

Neformalni pregled
program je napisan java jezikom i sastoji se od dva fajla 
Start.java je jednostavan program koji prima unose i ispisuje rezultate
Calculator.java sadrzi simbole ya vrsenje matematickih operacija

Staticka analiza izvrsena pomocu SonarLinta:
Calculator.java nije projektni fajl [ Ln 1, Col 2]
Dodati privatni konstruktor kako bi se sakrili implicitni javni [ Ln 4, Col 14 ]
Promeni metodu "ToString" u "toString" [ Ln 18, Col 30]
Preimenovati datoteku u imenovani paket [ Ln 1, Col 1]
Preimenovati ove metode tako da odgovaraju regularnom izrazu [ Ln 18, Col 30]
[ Ln 24, Col 26] [ Ln 74, Col 25}
Odmah vratiti ovaj izraz umesto da ga dodelite privremenoj variabli "textResult" [ Ln 70 , Col 29]
Ukloniti suvisan skok [ Ln 183, Col 13]
Start.java nije prijektni fajl [ Ln 1 , Col 1]
Zameniti ovu upotrebu Sistem.out ili Sistem.err zapisivacem [ Ln 8, Col 3]
[ Ln 19, Col 5]
Premestiti ovu datoteku u imenovani paket [ Ln 1, Col 1]
Promeniti ovu lokalnu variablu tako da odgovara regularnom izrazu [ Ln 6, Col 10]

