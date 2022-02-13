# Datensatz Spaetzle Connection Regierung Scholz #
Codebuch Stand 2022-02
erstellt von Swaran Sandhu (sandhu@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

# EDGE-Attribute

**from**  

**to**  

**relationship**
(1) Ministerium (auch angegliedert als Staatsekretär:in)
(2) politische Funktionen
(3) Ehrenamt
(4) Unternehmen und Aufsichtsräte
(5) Stipendien
(6) Berufstätigkeiten
(7) Studienort in In- und Ausland

**year**  
Bezieht sich auf das Jahr, in dem die Variable relationship beginnt

# NODE-Attribute  

-   name_short (Nachname)
-   name (voller Name)
-   type (0 = Person, 1 = Organisation/Ort/Verband etc.),
-   sex (Geschlecht)
-   birth (Geburtsjahr)
-   position (jetzige Position, z.B. Staatssekretär:in, Minister)
-   education (höchster Bildungsabschluss)
-   subject (Fachrichtung bei Studium/Promotion)
-   party (Parteizugehörigkeit)
-   religion (Religion)
-   kids (Anzahl der Kinder)
-   twitter (Anzahl follower)
-   instagram (Anzahl follower)
-   facebook (Anzahl follower)
-   youtube (Anzahl Abonnenten)

**id**  
Identische ID wie aus der edgelist zur eindeutige Identifikation der Knoten

**name_short**
kürzere Bezeichnung der Organisation, Beruf oder Nachname

**type**

**sex**    
Bitte geben Sie ihr Geschlecht an:  
1 = weiblich  
2 = männlich  
3 = divers
  
**crpr***    
Welche Studienrichtung haben Sie vertieft?  
1 = CR  
2 = PR

**height**  
Größe in cm   

**weight**  
Gewicht in kg  

**age_real**   
Alter in natürlichen Zahlen.  

**age**   
Bitte geben Sie Ihr Alter an:  
1 = bis 20 Jahre    
2 = 21 bis 22 Jahre    
3 = 23 bis 24 Jahre  
4 = 25 und älter  

**smoke**    
Rauchen Sie mindestens ein Mal pro Woche?  
1 = nein   
2 = ja  
  
**tatoo**    
Tatoo vorhanden?   
1 = nein  
2 = ja  

**phone**  
1 = android  
2 = iOS/iphone  
  
**eyes**    
Welche Augenfarbe?    
1 = grün,   
2 = blau,   
3 = braun,   
4 = blau.     

**hair**  
Welche Haarfarbe?  
1 = braun,      
2 = schwarz,   
3 = blond,    
4 = rot.    

**location** 
Wohnort, als string/characters codiert  

**county**  
Bundesland, als string/characters codiert  


##
