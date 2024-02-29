@qui Ciao ragazzi,<br>
Esercizio di oggi: **DB First**<br>
nome repo: `db-first`

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.
Non sono sicuro del fatto che possiate caricare direttamente un Excel, chiedo conferma a 
@Michele Spiller
 e 
@Marius Minia

Buon lavoro e a domani!



Colonne|Tipo|Attributi
---|---|---
id|BigInt|PRIMARY_KEY AUTO_INCREMENT
marca|VARCHAR|NOTNULL
modello|VARCHAR|NOTNULL
anno|DATE|NOTNULL
chilometraggio|MEDIUMINT|NOTNULL
tipo_cambio|VARCHAR|NOTNULL
alimentazione|VARCHAR|NOTNULL
potenza|INT|NOTNULL
carozzeria|VARCHAR|NOTNULL
potenza|SMALLINT|NOTNULL
cilindrata|VARCHAR(4)|NOTNULL
peso|INT|NOTNULL
consumo|VARCHAR|NOTNULL
classe_emissioni|VARCHAR(4)|NOTNULL
equipoggiamento|TEXT|NOTNULL
descrizione|TEXT|NOTNULL
prezzo|INT|NOTNULL
finanziamento| |NULL
telaio|CHAR(17)|UNIQUE,NOTNULL