# ESAME DI PROGRAMMAZIONE 

## ASP.NET CORE & SQL SERVER

Recupero - V1.0 - 092023

**Parte A: Sviluppo**

Hai il compito di sviluppare un'applicazione web utilizzando ASP.NET Core che gestisca l'informazione su libri e autori. 

**Requisiti del database:**

- Tavola `Autori`: 
    * `Nome`
    * `Cognome`
    * `DataDiNascita` (tipo data)
- Tavola `Libri`: 
    * `Titolo`
    * `DataPubblicazione` (tipo data)

**Requisiti dell'applicazione:**

1. Una pagina che permetta l'aggiunta di un nuovo autore.
2. Una pagina che permetta l'aggiunta di un nuovo libro e l'associazione di questo libro a un autore esistente.
3. Una pagina che elenchi tutti gli autori e i libri associati a ciascun autore.
4. Gestione di errori (es. tentativo di cancellare un autore che ha libri associati).

**Parte B: Domande sulle Query**

1. Scrivi una query per selezionare tutti gli autori che non hanno scritto nessun libro.
   
   ```sql
   SELECT ...
   ```

2. Scrivi una query per trovare il libro con la data di pubblicazione più recente.
   
   ```sql
   SELECT ...
   ```

3. Scrivi una query per contare quanti libri ha scritto ciascun autore e ordina il risultato in ordine decrescente basato sul numero dei libri.
   
   ```sql
   SELECT ...
   ```

4. Scrivi una query per selezionare gli autori che hanno scritto più di 3 libri.
   
   ```sql
   SELECT ...
   ```

5. Scrivi una query per aggiornare la `DataPubblicazione` di un libro specifico (ad es. `ID_Libro = 5`) a una nuova data (ad es. '2023-09-28').

   ```sql
   UPDATE ...
   ```

**Nota:** La sintassi SQL potrebbe variare leggermente in base alla versione e alle impostazioni specifiche di SQL Server.

### Come consegnare il compito:

Carica il progetto su GitHub e condividi la repository con "johnnypax" utente.

### DEADLINE: 09/09/2023