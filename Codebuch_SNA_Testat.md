
# CODEBUCH #		

#Datenerhebung 

Alle Daten wurden von der Webseite https://www.stuttgarts-schoenster-sport.de/team/spielerinnen entnommen. 

# EDGE-Attribute
			

FROM	
definiert Volleyballspielerin. Entspricht ID in der Nodelist.		

TO 	
definiert voherige Vereine oder das Heimtland der Spielerin. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 		
relation	Beziehungsart zwischen den Knoten 

(1 = Verein, 2 = Heimatland) 		
			
			
# NODE-Attribute			
ID	
Abkürzung des Spielernamens oder Organisation	

NAME	
Ausgeschriebener Name 		

SEX
Geschlecht (1 = male, 2 = female)	

TYPE
Unterschiedung zwischen Person, Organisation und Heimatland 

(1 = Person, 2 = Organisation, 3 = Heimatland)		

BIRTH 	
Geburtsjahr 		

AGE	
Alter 

(1 = unter 20, 2 = 21-23, 3 = 24-26, 4 = 27-30, 5 = über 30) 		

POSITION
Spielposition auf dem Feld 

( 1 = Mittelblock, 2 = Zuspiel, 3 = Außenangriff, 4 = Diagonal, 5 = Libera) 	

COUNTRY
Heimatland 

( 1 = Deutschland, 2 = Niederlande, 3 = Belgien, 4 = Bulgarien, 5 = Polen, 6 = USA, 7 = Spanien, 8 = Finnland, 		
