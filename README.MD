#Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

AUTO_VENDITA

id - INT - UNISIGNED - PRIMARY_KEY - AUTOINCREMENT
targa - VARCHAR (7) - NOTNULL - UNIQUE
modello - VARCHAR(255) - NOTNULL
marca - VARCHAR(255) - NOTNULL
anno_immatricolazione - YEAR - NOTNULL
tipologia_auto - VARCHAR(255) - NOTNULL

posti_auto - TINYINT - UNISIGNED - NULL 
lunghezza_auto_metri - FLOAT(4,2) - NULL
peso_auto_kg - FLOAT(4,0) - NULL
porte_auto - TINYINT - UNISIGNED - NOTNULL
colore - VARCHAR(255) - NOTNULL

chilometri_km - DECIMAL(6,0) - NOTNULL
alimentazione - VARCHAR(255) - NOTNULL
cilindrata - TINYINT - UNISIGNED - NOTNULL
cavalli - VARCHAR(255) - NOTNULL
consumi_citta_l/hm - FLOAT(3,1) - NULL
consumi_autostrada_l/km - FLOAT(3,1) - NULL

optional - text - NOTNULL - DEFAULT(BASE)

incidenti  - text - NOTNULL - DEFAULT(NESSUNO)

anno_inizio_vendita - YEAR - NOTNULL
costo - DECIMAL(9,2) - NOTNULL 
incentivi_percentuale - DECIMAL(5,2) - NOTNULL - DEFAULT(0)
provenienza - VARCHAR(255) - NOTNULL
descrizione_storia - text - NOTNULL 
 
foto - VARCHAR(255) - NULL 








