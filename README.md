# DNA GYMCraft

Benvenuto in DNA GYMCraft, un progetto innovativo che utilizza algoritmi genetici per generare schede di allenamento personalizzate. Questa soluzione è stata sviluppata per offrire agli utenti un'esperienza di allenamento ottimizzata in base al loro livello di abilità, preferenze e luogo di allenamento.

## Descrizione del Progetto

### Struttura del Progetto

Il progetto è organizzato nei seguenti componenti principali:

1. **Dataset**
   - Il dataset (`gym_dataset2.csv`) contiene informazioni dettagliate sugli esercizi, come il livello di abilità, il tipo di esercizio, i gruppi muscolari coinvolti e altro ancora. Prima di eseguire il codice, assicurati di avere un dataset ben strutturato.

2. **Algoritmo Genetico**
   - L'algoritmo genetico è implementato nel modulo `genetic_algorithm.py`. Questo modulo gestisce la generazione casuale di schede di allenamento, il calcolo della fitness, la selezione dei genitori, la riproduzione (crossover) e la mutazione.

3. **Interfaccia Utente**
   - L'interfaccia utente è integrata nel codice principale. Gli utenti vengono guidati attraverso la fornitura del proprio livello di abilità, luogo di allenamento e feedback sulla scheda generata.

4. **Configurazione**
   - Puoi regolare la configurazione iniziale, come il numero di generazioni e il tasso di mutazione, nel codice principale (`GYMGA.ipynb`).

### Istruzioni per l'Esecuzione

1. Assicurati di avere il dataset correttamente formattato (`gym_dataset2.csv`) e collocato nella stessa directory del codice.
2. Esegui il file `main.py`.
3. Segui le istruzioni per inserire il tuo livello di abilità, il luogo di allenamento e fornire feedback sulla scheda generata.

## Vincoli e Requisiti

- **Python:** Il progetto richiede Python 3.x. Puoi installare le dipendenze necessarie eseguendo `pip install -r requirements.txt`.

- **Dataset:** Verifica che il dataset sia correttamente formattato secondo le specifiche richieste nel codice.

## Contribuire

Se desideri contribuire al progetto, sentiti libero di aprire issue o pull request. Siamo aperti a miglioramenti e suggerimenti per rendere DNA GYMCraft ancora più efficace e personalizzabile.

Grazie per l'interesse nel progetto DNA GYMCraft! Buon allenamento!
