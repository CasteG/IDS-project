# IDS-project

## ISTRUZIONI PER ESEGUIRE IL CODICE:

Il progetto consiste nell'analisi di due diversi dataset: UNSW-NB15 e CSE-CIC-IDS2018.

###  SCARICARE I DATASET

- CSE-CIC-IDS2018: Per scaricare il dataset, aprire il link https://www.unb.ca/cic/datasets/ids-2018.html e seguire le istruzioni alla fine della pagina. Conviene però scaricare solo la parte interessata (l'intero dataset è molto grande), ovvero la sottocartella "PRE Processed Traffic Data for ML Algorithms". Al suo interno ci sono diversi file CSV, quello che ho utilizzato è "Friday-16-02-2018_TrafficForML_CICFlowMeter.csv"

- UNSW-NB15: Accedere alla pagina ufficiale del dataset https://research.unsw.edu.au/projects/unsw-nb15-dataset. Cliccare su "HERE" e nella cartella "CSV Files" scaricare i seguenti file: UNSW-NB15_1.csv, UNSW-NB15_2.csv, UNSW-NB15_3.csv, UNSW-NB15_4.csv

### ESEGUIRE IL CODICE

I file sono denominati con il nome del dataset, seguito dalla versione del codice. In ogni file, c'è una breve descrizione in alto che illustra le modifiche rispetto alle versioni precedenti.

Per eseguire il codice, ho utilizzato l'estensione Remote-SSH di VSCode. Mi sono connessa a una macchina virtuale fornita da CloudLab e ho copiato tutti i file (dataset e codice) in una cartella.

### LIBRERIE NECESSARIE

Assicurarsi di avere le seguenti librerie installate nel proprio ambiente:
- pandas 2.0.0 (ho dovuto fare un downgrade perchè la 2.2.2 mi dava problemi)
- scikit-learn 1.5.1
- tensorflow 2.17.0
- numpy 1.26.4
