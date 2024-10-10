Questo repository GitHub contiene il materiale relativo al progetto realizzato nel corso di Fondamenti di Data Science & Machine Learning. Il progetto si concentra sulla generazione di immagini tramite un modello di linguaggio di grandi dimensioni (LLM), esplorando sia l'aspetto etico che quello non etico della generazione di contenuti visivi.

File:
Generative_(Unethical).ipynb:

Questo file Jupyter Notebook contiene il codice implementativo del progetto.
È stato sviluppato un LLM capace di generare immagini in risposta a input testuali.
Per garantire la creazione di immagini etiche, è stato implementato un filtro sul prompt, che verifica l'assenza di "parole bannate".
Per quanto riguarda le immagini non etiche, sono stati utilizzati prompt automatici progettati per aggirare i filtri e generare contenuti inappropriati.


Paper_ProgettoFDSML.pdf:

Questo documento è un paper riassuntivo del lavoro svolto.
Presenta un’analisi dell'implementazione dell'LLM e descrive le metodologie utilizzate per bypassare i filtri imposti per la generazione di immagini non etiche.
Include anche discussioni sui rischi e le implicazioni etiche legate a tale tecnologia.


datasetEthical&NonEthical.pdf:
Questo file presenta un campione delle immagini generate, suddivise in etiche e non etiche, insieme ai relativi prompt utilizzati per la loro generazione.
Fornisce un'illustrazione pratica dei risultati ottenuti dall'LLM e delle differenze tra i due tipi di contenuti.


Prompt.pdf:

In questo documento sono riportate le immagini prodotte da ChatGPT in risposta a prompt maligni (cioè quelli che non hanno superato i filtri dell'LLM) e prompt benigni (quelli che sono riusciti a bypassare i filtri).
Questo confronto offre una visione chiara su come i filtri riescano a gestire e differenziare tra input etici e non etici.
