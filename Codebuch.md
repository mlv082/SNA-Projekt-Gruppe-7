# Datensatz SNA Projekt Gruppe 7 #
Codebuch Stand 2022-03, aktualisiert 2022-03
erstellt von Projekt Gruppe 7 

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Der Datensatz unter den Abgeordneten des Bundestages kommend aus Baden-Württemberg Wahlperiode xyz wurde mithilfe Wikipedia und der Selbstauskunft auf bundestag.de erhoben.

Das Netzwerk ist ein *ungerichtetes two-mode Akteurs-Einrichtungsnetzwerk*.


##Nodes

sex     
1=female	   
2=male	    
3=keine Information/ nicht relevant	   


type
1=Einrichtung       
2=Person      

party      
1=CDU/CSU      
2=SPD     
3=Grüne     


Herkunft Bundesland    

1=Bayern       
2=Baden-Württemberg       
3=Rheinland-Pfalz       
4=Saarland       
5=Hessen        
6=Thüringen      
7= Sachsen      
8=Nordrhein-Westfalen     
9=Sachsen-Anhalt      
10= Niedersachsen      
11= Brandenburg     
12= Schleswig-Holstein      
13=Mecklenburg-Vorpommern         
14=Bremen        
15=Hamburg         
16=Berlin        

Historie Bundesland          
1=BRD       
2=DDR        


age      
1= 18-25       
2= 26-50      
3= 51-99         

erster Abschluss        
1= Realschulabschluss	    
2=Abitur	  
3=Hochschulabschluss	  
4=Universitätsabschluss	       

zweiter Abschluss        
1= Abitur	    
2=Fachhochschulreife	  
3=Hochschulabschluss	  
4=Universitätsabschluss 	      
5= kein         	

dritter Abschluss     
1= Abitur	   
2=Fachhochschulreife	  
3=Hochschulabschluss	
4=Universitätsabschluss	
5= kein 3. Abschluss	  

Praktiker         
1=ja      
2=nein      

Hochschulabschluss      
0=kein Hochschulabschluss      
1=Bachelor     
2=Master      
3= Promotion        
4= Professur        
5 = Staatsexamen         

Fachrichtung    
1= Technik	   
2= Naturwissenschaften	   
3= Medizin	   
4= Medien & Marketing	   
5= Soziales	     
6= Rechtswissenschaften      
7= Beamter(Verwaltung)	   
8= Politikwissenschaften	    
9= Wirtschaft	    
10= Militär	    


Typ Einrichtung      
1= Hochschule	  
2= Universität	  
3= Berufsausbildung/Job	    
4=Förderprogramm	    

Ranking Einrichtung      
1= ja     
2= nein      

Zugehörigkeit      
1=staatlich    
2=privat     
3=kirchlich   

Country     
1= Deutschland     
2 = nicht DE     



##Edges      
from	

Bundestagsabgeordneter	   

to	   
Bildungseinrichtung    
    Förderprogramm	      	
    Jobstation      
    
    
weight       
1= 2 Jahre     
2= 3-4 Jahre      
3= 5-10 Jahre       

relation     
1= Ausbildung      
2= Job      
3= Förderung      








