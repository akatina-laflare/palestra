# Palestra · Ghisa Coach

App web in italiano per seguire l'allenamento in palestra, in un unico file (`index.html`), senza dipendenze da installare.

## Cosa fa

- **Scheda personalizzata**: full body e misti oppure divisa per gruppo muscolare, da 2 a 6 giorni a settimana, con serie, ripetizioni e recuperi in base all'obiettivo (dimagrire, tonificare, massa, forza).
- **Allenamenti per gruppo muscolare**: petto, dorso, gambe, spalle, bicipiti, tricipiti, glutei, addome, cardio.
- **Registro dell'allenamento**: chili e ripetizioni per ogni serie, timer di recupero, suggerimenti di progressione in base alla volta precedente.
- **105 esercizi** con animazione del movimento, passaggi, errori da evitare e alternative. Ogni esercizio della scheda si può sostituire.
- **Nutrizione**: calorie (formula Mifflin-St Jeor), proteine, carboidrati, grassi, acqua e fibre, divisione nei pasti ed equivalenze tra alimenti.
- **Timer**: For Time, AMRAP, EMOM, Tabata, intervalli e Mix, con conto alla rovescia, voce e suoni, contagiri con tempi di ogni giro, schermo sempre acceso e storico.
- **Circuiti**: 8 circuiti pronti (bruciagrassi, HIIT, gambe e glutei, addome, parte alta, manubri, kettlebell, macchine) con timer integrato, animazione dell'esercizio in corso e voce che annuncia il prossimo. Lavoro, recupero e giri si possono modificare.
- **Riscaldamento guidato**: 5 riscaldamenti da 4–6 minuti (generale, gambe, parte alta, schiena, cardio) con timer, animazioni e voce che dice quando cambiare lato. In Oggi l'app propone quello adatto all'allenamento del giorno e alla fine fa partire l'allenamento.
- **Calcolo dei pasti**: scrivi cosa hai mangiato (es. «80 g di pasta al pomodoro, un cucchiaio d'olio, 150 g di pollo, una mela») e l'app calcola calorie e macronutrienti da una tabella di circa 130 alimenti. Funziona senza connessione e senza chiave API; le quantità si correggono e il pasto si salva nel diario.
- **Progressi**: pesate con media mobile a 7 giorni, record personali con massimale stimato, storico degli allenamenti e dei timer.
- **Grafica liquid glass**, tema chiaro e scuro, colore principale a scelta, gesti (swipe tra le sezioni, trascinare per chiudere).

## Come usarla

Apri `index.html` in un browser. I dati vengono salvati nel browser del dispositivo.

Solo il coach e il menù del giorno usano Claude (facoltativi):

- aperta come Artifact su claude.ai, l'app usa l'account Claude di chi la apre;
- come web app (per esempio da GitHub Pages) usa l'API di Claude con una chiave personale, da inserire in Profilo → Coach AI. La chiave resta solo nel browser del dispositivo e i costi vanno sull'account API.

Il salvataggio nell'account Claude funziona solo su claude.ai; nella web app i dati restano nel browser.

## Nota

Le indicazioni su allenamento e alimentazione sono generali e non sostituiscono medico o nutrizionista.
