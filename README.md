Come funziona la query
•	Si collegano i treni alle tratte tramite la tabella di relazione Treno_Tratta.
•	Con un LEFT JOIN si contano tutti i biglietti venduti per ogni tratta assegnata al treno, anche se non ci sono biglietti venduti (mostrando così zero).
•	Si calcola la percentuale di occupazione come il rapporto tra biglietti venduti e capienza del treno, moltiplicato per 100.
•	I risultati sono ordinati in modo decrescente per evidenziare le tratte più occupate.
