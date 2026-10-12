# Bertorotta Listini

Versione aziendale indipendente derivata da ListinoHub, licenza MIT (vedere LICENSE).

## Avvio
Caricare il contenuto della cartella su hosting HTTPS, per esempio `/listini/`, quindi aprire `index.html`. Nessun database MySQL necessario.

## Listini multipli
Per ogni fornitore compilare nome e impostazioni, caricare CSV, XLS o XLSX. La gestione dei duplicati consente sostituzione o mantenimento di listini separati. Cercare poi articoli per codice, descrizione o fornitore.

## Attenzione ai dati
I listini sono conservati nel browser/dispositivo (IndexedDB), non su un database centrale. Effettuare regolarmente il backup dall'app: non condividono automaticamente i listini tra PC e utenti. Non cancellare i dati del sito senza backup.

## Personalizzazione
Logo e colori Bertorotta, nuova identità PWA, database browser separato dalla versione originale. La logica di importazione e preventivazione resta quella del progetto sorgente.
