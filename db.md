
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

#table name: cars (entity name:car)

colums:

-id BIGINT AUTO_INCREMENT UNIQUE NOT NULL
-?marca 
-?modello 
-carrozzeria VARCHAR(25) NOT NULL
-carburante VARCHAR(20) NOT NULL
-km INT FLOAT(8,2) NOT NULL
-prezzo  SMALL FLOAT(8,2) NOT NULL
-data immatricolazione DATE NOT NULL
-targa TINYINT NOT NULL
-porte TINYINT NOT NULL
-cambio VARCHAR(25) NOT NULL
-posti TINYINT NOT NULL
-colore carrozzeria VARCHAR(15) NOT NULL
-colore interni VARCHAR(15) NOT NULL
-incidentata TINYINT DEFOULT(0) NULL
-?optional