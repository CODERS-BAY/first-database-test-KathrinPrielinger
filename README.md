# DB-Test
## Aufgabe 1
Stelle Entitäten mittels Chen-Notation und Min,Max Notation dar.
Wähle ein sinnvolles Beispiel!

  ## Aufgabe 2
  Kann eine Beziehung Attribute haben?
  ja

Wenn ja, wie stelle ich es im ERD dar?

  ## Aufgabe 3
  Welche Codd'schen Anforderungen gibt es (Nenne mindestens 5)
  Integration, Operation, Katalog, Benutzersichten, Integritätssicherung, Zugriffskontrolle, Transaktion, Synchronisation, Datensicherung
  
  ## Aufgabe 4
  Nenne den Unterschied zwischen Konzeptuellen und Logischem Schema
  Konzeptuelles Schema: Darstellung in Wolken von Entities und Attributen.
  Logisches Schema: Entities und Relations sind verbunden, die Attribute werden ihnen zugwewiesen.

  ## Aufgabe 5
  Welche 3 Bestandteile gibt es im Entity Relationship Model
  Entitäten
  Attribute
  Beziehungen
  
  ## Aufgabe 6
  Welche Datentypen gibt es in SQL? (Nenne mindestens 5)
  varchar
  integer
  date
  double
  time
  
  ## Aufgabe 7
  Welche Arten von Schlüsseln gibt es und welche Eigenschaften besitzen diese?
  Pimärschlüssel: Identifiziert die Tabelle eindeutig,kommt nur 1x in der Tabelle vor, er kann generiert werden oder ein natürlicher Schlüssel sein.
  Sekundärschlüssel: Fremdschlüssel, er verweist auf eine andere Tabelle
  
  ## Aufgabe 8
  Welche Arten von Beziehungen gibt es? Zeichne für jede ein Beispiel auf
  Es gibt 1:n (Eins zu Viele), 1:1 (Eins zu Eins), n:m (Viele zu Viele)-Beziehungen.

  ## Aufgabe 9
  Was bedeutet der Begriff Kardinalität und welche Kardinalitäten gibt es?
  Kardinalität ist im Zusammenhang mit DB eine Tabelle mit Daten und die darin enthaltenen Zeilen und Spalten.
  Kardinalität einer Spalte
  Kardinalität einer Zeile
  

## Aufgabe 10
Was bedeutet der Begriff Datenintegrität und worin unterscheidet sich Integrität und referentielle Integrität?
  Datenintegrität: Korrektheit der Daten
  Integrität:
  referentielle Integrietät: Korrektheit der Beziehungen
  
  ## Aufgabe 11
  Erkläre die 3 Normalformen
  1. Normalform:
  Ein Relationstyp (Tabelle) befindet sich in der ersten Normalform (1NF), wenn die Wertebereiche der Attribute des Relationstypen atomar sind.
  Ein Relationenschema befindet sich in der 1. Normalform, wenn alle seine Attribute einfach und einwertig sind.
  Um die 1. Normalform zu erreichen, muss für jeden Wert eines mehrwertigen Attributes ein separates Tupel erzeugt werden. 
  
  2. Normalform:
  Ein Relationstyp (Tabelle) befindet sich genau dann in der zweiten Normalform (2NF), wenn er sich in der ersten Normalform (1NF) befindet und jedes Nichtschlüsselattribut von jedem     
  Schlüsselkandidaten voll funktional abhängig ist.
  Ein Relationenschema ist in der 2. Normalform, wenn es in der 1. Normalform ist und wenn jedes nicht zum Identifikationsschlüssel gehörige Attribut von diesem voll funktional
  abhängig ist. 
  
  3. Normalform:
  Ein Relationstyp befindet sich genau dann in der dritten Normalform (3NF), wenn er sich in der zweiten Normalform (2NF) befindet und kein Nichtschlüsselattribut transitiv von einem
  Kandidatenschlüssel abhängt.
  Ein Relationenschema befindet sich in der 3. Normalform, wenn es in der 2. Normalform ist und kein Attribut, das nicht zum Identifikationsschlüssel gehört, von diesem transitiv ()
  abhängt. 
 
  ## Aufgabe 12
  Erkläre den Unterschied zwischen starken und Schwachen Entitäten und erstelle ein Beispiel.
  Eine schwache Entität ist nur in Kombination mit dem Primärschlüssel einer starken Entity identifizierbar.


  ## Aufgabe 13
  Welche Grundregeln gibt es im Relationenmodell? (Nenne mindestens 4)
  Datenwerte sind atomar,
  Zeilen- und Spaltenreihung sind ohne Bedeutung,
  Es gibt immer nur einen Primärschlüssel,
  Fremdschlüssel werden strichliert unterstrichen,
  Primärschlüssel werden unterstrichen

  ## Aufgabe 14
  Wie löst man eine M:N Beziehung auf? Erstelle ein Beispiel


## Aufgabe 15
Ein Handelsbetrieb verkauft ein Sortiment von Artikeln, die er von verschiedenen Herstellern bezieht. Der Handelsbetrieb hat einen bestimmten Kundenkreis, der regelmäßig Bestellungen aufgibt. Eine Bestellung kann mehrere Artikel umfassen. Ein Artikel kann von mehreren Lieferanten bezogen werden und ein Lieferant liefert natürlich meist mehr als einen Artikel. Erstelle ein ERD und ein Relationenmodell, welches der 3. Normalform entspricht.

  ## Aufgabe 16
  Welche Anomalien kennst du und was beschreiben sie?
Erstellungsanomalie: Es sollen nur so viele Daten eingegeben werden wie vorhanden sind, Änderungsanomalie: Es sollen nur die Daten geändert werden die notwendig sind, Löschungsanomalie: Es sollen nur so viele Daten gelöscht werden, wie notwendig, sonst entsteht eine Anomalie

## Aufgabe 17
Modellieren Sie den angeführten Realitätsausschnitt einer Fluggesellschaft mit Hilfe eines Entity Relationship- Diagramms. Treffen Sie, falls notwendig, sinnvolle Annahmen und dokumentieren Sie diese nachvollziehbar in Ihrer Lösung. Der zu betrachtende Realitätsausschnitt der Fluggesellschaft umfasst folgenden
Sachverhalt:
Flughäfen haben ein Kürzel (= Schlüssel) und gehören zu einer Stadt (z.B. „FRA“ für Frankfurt, „FCO“ für Roma Fiumicino).
Flüge haben eine Flugnummer (z.B. „LH 306“), führen von einem Flughafen zu einem anderen, mit jeweils einer festen Abflugs- und Ankunftszeit (z.B. ab Frankfurt um 07:30 nach Roma Fiumicino mit Ankunft um 09:15).
Jeder Flugzeugtyp hat einen Namen (z.B. „747-400“) und eine Sitzanzahl (z.B. 430 Sitze).
Piloten haben einen Namen (z.B. „Meier“), ein Geburtsdatum (z.B. „1.1.1960“) und eine Berechtigung, bestimmte Flugzeugtypen zu fliegen (z.B. „747-400“ und „A310“).
Jedes einzelne Flugzeug ist von einem bestimmten Flugzeugtyp (z.B. „747-400“) und hat einen Namen (z.B. „Mozart“).
Bei einem Flug-Einsatz wird ein Flug (z.B. „LH 306“) an einem bestimmten Datum (z.B. „6.2.2011“) von einem bestimmten Piloten (z.B. „Meier“) mit einem bestimmten Flugzeug (z.B. „Mozart“) geflogen.
Bilden Sie das konzeptuelle Schema in ein relationales Schema ab. Das relationale Schema soll der 3. Normalform genügen
