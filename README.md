# IDS-project

ISTRUZIONI PER ESEGUIRE IL CODICE

Il progetto consiste nell'analisi di due diversi dataset: UNSW-NB15 e CSE-CIC-IDS2018.

A) SCARICARE I DATASET

- CSE-CIC-IDS2018: Per scaricare il dataset, installare AWS CLI (https://aws.amazon.com/cli/) ed eseguire il seguente comando:
aws s3 ls --no-sign-request --region ca-central-1 "s3://cse-cic-ids2018/PRE Processed Traffic Data for ML Algorithms/Friday-16-02-2018_TrafficForML_CICFlowMeter.csv"

- UNSW-NB15: Accedere alla pagina ufficiale del dataset https://research.unsw.edu.au/projects/unsw-nb15-dataset. Cliccare su "HERE" e nella cartella "CSV Files" scaricare i seguenti file:
UNSW-NB15_1.csv UNSW-NB15_2.csv UNSW-NB15_3.csv UNSW-NB15_4.csv

B) ESEGUIRE IL CODICE

- Codice per UNSW-NB15: I file relativi al dataset UNSW-NB15 sono denominati con il nome del dataset, seguito dalla versione del codice. In ogni file, c'è una breve descrizione in alto che illustra le modifiche rispetto alle versioni precedenti.

- Codice per CSE-CIC-IDS2018: I file relativi al dataset CSE-CIC-IDS2018 comprendono il resto del codice. In questo caso esistono due modelli distinti: uno binario e uno multiclasse. Sono facilmente distinguibili dal titolo del file.

Per eseguire il codice, ho utilizzato l'estensione Remote-SSH di VSCode. Mi sono connessa a una macchina virtuale fornita da CloudLab e ho copiato tutti i file (dataset e codice) in una cartella.

C) LIBRERIE NECESSARIE

Assicurarsi di avere le seguenti librerie installate nel proprio ambiente:
- pandas 2.0.0 (ho dovuto fare un downgrade perchè la 2.2.2 mi dava problemi)
- scikit-learn 1.5.1
- tensorflow 2.17.0
- numpy 1.26.4
