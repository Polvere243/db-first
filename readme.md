Ciao ragazzi,
Esercizio di oggi: DB First
nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.
Non sono sicuro del fatto che possiate caricare direttamente un Excel, chiedo conferma a 
@Michele Spiller
 e 
@Marius Minia
Buon lavoro e a domani!

Nome | Tipo | Attributi
--| -- |--
id | TINYINT | PRIMAY_KEY UNSIGNED
marca | VARCHAR | NOTNULL
modello | VARCHAR | NOTNULL
anno_immatricolazione| DATE | NOTNULL
Km_percorsi | FLOAT(3,2) | UNSIGNED NOTNULL
danni | VARCHAR | NOTNULL
multe | VARCHAR | NOTNULL
incidenti | VARCHAR | NOTNULL
condizioni| TEXT   | NOTNULL
data_acquisizione | DATE | NULL
costo | TINYINT | NULL


