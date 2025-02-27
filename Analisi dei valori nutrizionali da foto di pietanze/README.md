# **Analisi Automatica dei Valori Nutrizionali da Foto di Pietanze**  

## **Caso d'uso aziendale: Serenis**  

### **Introduzione all'azienda**  

Serenis è il principale centro medico online dedicato al benessere fisico e mentale, con un focus su psicologia, psichiatria, coaching e nutrizione. Attraverso la piattaforma, gli utenti possono prenotare sedute con nutrizionisti professionisti e avviare il proprio percorso nutrizionale in pochi minuti.  

### **Problema**  

Monitorare la propria alimentazione richiede un'analisi accurata dell’apporto calorico e della suddivisione dei macronutrienti (carboidrati, proteine e grassi). Le app attualmente disponibili impongono agli utenti di inserire manualmente gli alimenti consumati, un processo lungo e macchinoso che porta spesso all’abbandono dell’utilizzo dopo poco tempo. Per questo motivo Serenis vuole prototipare una soluzione che utilizza l'intelligenza artificiale per automatizzare il monitoraggio dell'alimentazione degli utenti.

### **Obiettivo del progetto**  

L'obiettivo del progetto è sviluppare un sistema di intelligenza artificiale capace di riconoscere automaticamente una pietanza a partire da un'immagine e restituire il suo apporto calorico e il contenuto di macronutrienti. Questo semplificherà il monitoraggio della nutrizione, rendendo il processo più immediato ed efficace per l'utente.  

### **Specifiche tecniche**  

Il software dovrà essere in grado di:  
1. **Identificare la pietanza** presente in un'immagine fornita dall’utente.  
2. **Calcolare il valore nutrizionale** (calorie e macronutrienti) considerando una porzione media.  

Per l’addestramento del modello e il calcolo dei valori nutrizionali, saranno forniti dataset dedicati.  

### **Restrizioni**  

- Non è consentito l’uso di modelli di linguaggio (LLM).  
- Il modello di deep learning dovrà essere addestrato da zero o tramite **transfer learning** a partire da un modello pre-addestrato.  
- Il framework da utilizzare è **PyTorch**.

## **Dataset**
1. [Immagini di pietanze](https://proai-datasets.s3.eu-west-3.amazonaws.com/foods-25.zip)
2. [Valori nutrizionali](https://github.com/Profession-AI/progetti-serenis/raw/refs/heads/main/Analisi%20di%20macronutrienti%20di%20alimenti%20da%20foto/nutritional_values.csv)
