# Datensatz Netzwerkanalyse Anne Frank #
### Luisa, Celine, Kai, Julia, Sandra, Theresa  ###

## Inhalt
- el.csv (Edgelist)
- nl.csv (Nodelist)
- codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Auf Grundlage des Anne Frank Tagebuchs, sowie weiterer Lektüre haben wir ein Netzwerk über Anne Franks Sozialbeziehungen erstellt. 

Unser Gesammtnetzwerk ist ein ungerichtetes two-mode Netzwerk, das durch weitere, gewichtete Teilnetzwerke ergänzt wird. 


## EDGE-Attribute 

ID  
codiert von 1 bis XX, jede ID entspricht einer Person bzw. einem Gegenstand.

#### Werte, die nicht verfügbar sind, werden mit "NA"gekennzeichnet 

#### WEIGHT  

Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen:

1 = Neutral 
2 = Gering (negative Emotionen)
3 = Mittel (Freundschaftliche Beziehung)
4 = Stark (starke Zuneigung)
5 = Sehr stark (Liebe) 

#### RELATIONSHIP 

Definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. 

1 = Familie
2 = Kontakt
3 = Freundschaft

#### KONFLIKTPOTENZIAL

Definiert die Häufigkeit von Konfliketen und potentiellen Konflikten.

1 = nie
2 = sehr selten
3 = ab und zu 
4 = häufig 

#### TIME DEFINITION

Einteilung der Zeitabschnitte in normalisierten Werten

1 = Frankfurt (Geburt Juni 1929 - Februar 1934) 
2 = Amsterdam - Umzug ins Hinterhaus (XX 1934-1942 XX) 
3 = Hinterhaus Teil 1 (1942 XX - 31. Dezember)
4 = Hinterhaus Teil 2 (1943 Janaur - Dezember) 
5 = Hinterhaus Teil 3 (1944 Janaur - XX Aufgeflogen) 
6 = Nach dem Krieg (Januar 1946)   
7 = vor Annes Geburt (1929 und früher)


## NODE-Attribute  
  
#### SEX  

Gibt das Geschlecht an

1 = männlich
2 = weiblich
3 = neutrum 
  

#### RELIGION

Definiert die Religion der Akteure 
1 = Jude
2 = Christ
3 = sonstiges 

#### SURVIVAL

Todeszeitraum in Korrelation zu den Weltkriegen

1 = vor dem Ersten Weltkrieg verstorben
2 = während des Ersten Weltkriegs verstorben
3 = vor dem Zweiten Weltkrieg verstorben 
4 = unabhängig des Zweiten Weltkriegs nach 1945 verstorben


#### TYPE OF DEATH

Definiert die Todesursache.
1 = Vergasung 
2 = Fahrlässige Tötung im KZ 
3 = Natürlicher Tod

#### PLACE OF DEATH

Definiert den Todesort

1 = KZ Bergen-Belsen
2 = Birsfelden
3 = KZ Auschwitz-Birkenau
4 = KZ Bergen-Belsen
5 = KZ Auschwitz-Birkenau
6 = Transport nach Theresienstadt
7 = KZ Mauthausen
8 = KZ Neuengamme
9 = Anderer Todesort

#### TYPE

Definiert den Typ des Knotens

1 = Mensch
2 = Gegenstand (Tagebuch)
