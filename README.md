## Progetto: Robustezza dei Modelli di Machine Learning su Dati Contaminati

### Obiettivo
Analizzare l’impatto della contaminazione dei dati sulle prestazioni dei modelli di machine learning e identificare le feature più influenti.

### Fasi del progetto

1. **Scelta del Dataset**  
   Seleziona un dataset adeguato per il problema da analizzare (è consentito anche l'uso di generatori sintetici che mantengano la distribuzione originale).

2. **Esplorazione dei Dati (EDA)**  
   Analizza la distribuzione delle feature, la presenza di valori mancanti, correlazioni e altre statistiche descrittive utili.

3. **Scelta dei Modelli**  
   Scegli **due modelli di machine learning** adatti al problema (classificazione o regressione).

4. **Baseline Model**  
   Addestra i modelli sul dataset originale (pulito) per ottenere una baseline delle prestazioni.

5. **Contaminazione Progressiva del Dataset**  
   Introduci in modo controllato varie tecniche di sporco sui dati, tra cui:
   - Aggiunta di rumore
   - Rimozione o sostituzione di feature
   - Inserimento di valori casuali o outlier
   - Duplicazione di campioni

6. **Valutazione delle Prestazioni**  
   Valuta i modelli su dataset contaminati usando metriche appropriate (accuracy, precision, recall, F1-score, ecc.).

7. **Confronto con il Baseline**  
   Confronta le prestazioni dei modelli puliti vs contaminati. Analizza quali feature influiscono maggiormente.

8. **Interpretazione dei Risultati**  
   Spiega il comportamento dei modelli di fronte ai dati sporchi. Evidenzia le feature critiche e gli effetti del loro sporco.

9. **Conclusioni**  
   Rifletti sull'efficacia delle tecniche di contaminazione per l'analisi dell'importanza delle feature. Proponi miglioramenti o sviluppi futuri.
