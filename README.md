Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Nella repo dovete consegnare un file con tutti i campi della tabella, tipo di dato ed eventuali attributi per ogni campo.


**Soluzione**
Entità:

- 1  Macchine: 
    attributi:
    CarID
    Marca
    Modello
    Anno
    Kilometri
    Prezzo
    Cambio
    Alimentazione
    Colore:
    Cilindrata:
    ProprietarioId
    AcquirenteId
- 2 Proprietario:
    SellerID
    SellerName
    SellerEmail
    SellerPhone
    SellerLocation
- 3 Acquirente:
    ClientID
    ClientName
    ContactEmail
    ContactPhone
- 4 RIPARAZIONI:
    ReparationId
    CarID
    ReparationDate
    ReparationDescription,
    ReparationCost,
- 5 TAGLIANDO: 
    TagliandoID,
    CarID,
    CostoTagliando,
    DataTagliando,
    DescTagliando,
    OraTagliando
