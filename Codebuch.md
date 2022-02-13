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
-   twitter (Anzahl follower)
-   instagram (Anzahl follower)
-   facebook (Anzahl follower)
-   youtube (Anzahl Abonnenten)

**id**  
Identische ID wie aus der edgelist zur eindeutige Identifikation der Knoten

**name_short**
kürzere Bezeichnung der Organisation, Beruf oder Nachname

**type**
0 = Person, 1 = Organisation/Ort/Verband etc.

**sex**    
1 = weiblich  
2 = männlich  
3 = divers
  
**birth***    
Geburtsjahr

**position**  
jetzige Position, z.B. Staatssekretär:in, Minister

** education **  
höchster Bildungsabschluss 

**subject**   
Fachrichtung bei Studium/Promotion

**party**   
Parteizugehörigkeit

**religion**    
Religion
  
**kids**    
Anzahl der Kinder

**twitter**  
1= bis 5.000
2= 5.000-10.000
3= 10.000-15.000
4= über 15.000
  
**facebook**    
1= bis 2.000
2= 2.000-4.000
3= 4.000-6.000
4= über 6.000

**instagramm**  
1= bis 2.000
2= 2.000-4.000
3= 4.000-6.000
4= über 6.000


**youtube** 
1= bis 50
2= 50-100
3= über 100


##