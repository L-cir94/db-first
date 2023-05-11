# db-first
| ID                             |       Marca       |                   Modello                   |      anno      |      km       | Descrizione |                  immagine                  |                 usura                  |                      prezzo                      | 
| :----------------------------- | :---------------: | :-----------------------------------------: | :------------: | :-----------: | :---------: | :----------------------------------------: | :------------------------------------: | :----------------------------------------------: |
| Primary key, not null, varchar, auto increment | not null, varchar(50), index | default(veicolo trasporto persone), varchar(50), index | not null, year, index | not null, varchar(6) 999999 | null, text  | null, varchar, default(immagine logo sito) | varchar, default(info non disponibili) | null, decimal(7,2) 999999,99 default(richiedi info scrivendoci), index |

