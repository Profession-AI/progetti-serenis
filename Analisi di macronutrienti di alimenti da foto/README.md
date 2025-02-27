# **Analisi Automatica dei Macronutrienti di un Alimento da una Foto**  

## **Caso d'uso aziendale: Serenis**  

### **Introduzione all'azienda**  

Serenis è il principale centro medico online dedicato al benessere fisico e mentale, con un focus su psicologia, psichiatria, coaching e nutrizione. Attraverso la piattaforma, gli utenti possono prenotare sedute con nutrizionisti professionisti e avviare il proprio percorso nutrizionale in pochi minuti.  

### **Problema**  

Monitorare la propria alimentazione richiede un'analisi accurata dell’apporto calorico e della suddivisione dei macronutrienti (carboidrati, proteine e grassi). Le app attualmente disponibili impongono agli utenti di inserire manualmente gli alimenti consumati, un processo lungo e macchinoso che porta spesso all’abbandono dell’utilizzo dopo poco tempo.  

### **Obiettivo del progetto**  

L'obiettivo del progetto è sviluppare un sistema di intelligenza artificiale capace di riconoscere automaticamente un alimento a partire da un'immagine e restituire il suo apporto calorico e il contenuto di macronutrienti. Questo semplificherà il monitoraggio della nutrizione, rendendo il processo più immediato ed efficace per l'utente.  

### **Specifiche tecniche**  

Il software dovrà essere in grado di:  
1. **Identificare l’alimento** presente in un'immagine fornita dall’utente.  
2. **Calcolare il valore nutrizionale** (calorie e macronutrienti) in base alla grammatura specificata.  

Per l’addestramento del modello e il calcolo dei valori nutrizionali, saranno forniti dataset dedicati.  

### **Restrizioni**  

- Non è consentito l’uso di modelli di linguaggio (LLM).  
- Il modello di deep learning dovrà essere addestrato da zero o tramite **transfer learning** a partire da un modello pre-addestrato.  
- Il framework da utilizzare è **PyTorch**.  