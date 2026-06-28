# App Quiz domande esame AGEA

Questa repository contiene una piccola app statica per esercitarsi sulle domande dell'esame AGEA.

## Come funziona

L'app è contenuta nel file `index.html` e funziona direttamente nel browser.

Funzioni principali:

- allenamento completo sulle domande;
- esame simulato da 15 domande;
- soglia di superamento: almeno 10 risposte corrette su 15;
- immagini incorporate nelle domande;
- risposte mescolate casualmente;
- modalità solo errori;
- modalità domande difficili;
- modalità ripasso finale;
- preparazione adattiva;
- statistiche e cronologia;
- esportazione/importazione dei progressi;
- salvataggio locale nel browser.

## Pubblicazione con GitHub Pages

1. Creare una nuova repository GitHub, ad esempio `quiz-agea`.
2. Caricare nella repository tutti i file contenuti in questo pacchetto.
3. Aprire `Settings` della repository.
4. Entrare in `Pages`.
5. In `Build and deployment`, scegliere `Deploy from a branch`.
6. Selezionare branch `main` e cartella `/root`.
7. Salvare.

Dopo qualche minuto l'app sarà accessibile all'indirizzo:

```text
https://TUO-USERNAME.github.io/quiz-agea/
```

## Note sui progressi

I progressi non sono salvati su GitHub. Sono salvati localmente nel browser dello studente tramite `localStorage`.

Questo significa che:

- se lo studente cambia browser o dispositivo, i progressi non vengono trasferiti automaticamente;
- se cancella i dati del browser, i progressi possono andare persi;
- per trasferire i progressi si può usare la funzione di esportazione/importazione presente nell'app.

## Nota importante

Il file HTML contiene anche le risposte corrette. L'app è quindi adatta come strumento di allenamento, non come piattaforma per somministrare un esame reale.
