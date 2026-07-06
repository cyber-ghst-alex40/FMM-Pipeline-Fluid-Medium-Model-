https://colab.research.google.com/drive/1HVe58Eg5Dr9noKasGKBPjN3xhLHa6MIG

FMM Pipeline – Fluid Medium Model for HST Data Analysis
Pipeline computazionale per l'analisi del modello di mezzo fluido (FMM) di file .flt del telescopio spaziale Hubble. Include notebook Google Colab riproducibili per l'elaborazione e la validazione del segnale.

📚 Descrizione
Questo repository contiene la pipeline ufficiale del Modello FMM (Fluid Medium Model), validata su dati reali del telescopio Hubble e attualmente in fase di pubblicazione su rivista peer-reviewed.

Il modello interpreta il mezzo intergalattico come un fluido viscoso in condizioni termodinamiche di non-equilibrio, operando esclusivamente su dati grezzi (.flt) senza l'uso di costanti di calibrazione (Zero Point, dark frame, flat-field).

Le metriche estratte includono:

X (flusso medio)

Y (flusso massimo, picco del nucleo)

Z (flusso totale integrato)

VDR (Residual Dynamic Vector, vettore dinamico residuo)

M_eff (massa efficace del sistema

Quesa pipeline si collega automaticamente allo studio condotto sulle morfologie galattiche ecc... nell'FMM model.

PIPELINE.ipynb – Notebook Google Colab completo

Dhnv (1).docx – Paper 1 (Modello Osservativo FMM)

Formazione_dell_universo_e_ercole_(9)_compressed.pdf – Paper 2 (Formazione Universo e Hercules


Apri il notebook in Google Colab.

Assicurati che i file siano inseriti tramite drive o che tutti vengano scaricati correttamente e risultino visibili nella cartella a sinistra, (se volete potete anche applicarvi dei seample)

La pipeline si collegherà automaticamente all'archivio MAST, scaricherà i dati .flt per il target selezionato, e restituirà:

Un tabellato di tutti i dati calcolati ed estratti

Grafici radiali e heatmap

Analisi VDR

Metriche energetiche (X, Y, Z, M_eff)

Indicatore di stabilità sistemica (rapporto stress galassia–buco nero)

Good science. 🚀
