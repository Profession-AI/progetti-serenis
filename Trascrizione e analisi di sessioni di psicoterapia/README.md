
# **Trascrizione e Analisi delle Sessioni di Psicoterapia**  

**Nota bene:** I dati utilizzati in questo progetto sono interamente sintetici. ProfessionAI li ha generati tramite diversi sistemi di intelligenza artificiale per simulare sessioni di psicoterapia.  

## **Caso d'uso aziendale: Serenis**  

### **Introduzione all'azienda**  

Serenis è il principale centro medico online dedicato al benessere fisico e mentale, con un focus su psicologia, psichiatria, coaching e nutrizione. La piattaforma consente di prenotare sedute online con psicoterapeuti e psichiatri, ovvero professionisti che, dopo la laurea in psicologia o medicina, hanno conseguito una specializzazione.  

### **Problema**  

Il lavoro degli psicoterapeuti è estremamente complesso, poiché si confrontano quotidianamente con la mente umana, il sistema più sofisticato e ancora in gran parte inesplorato.  

Sebbene l'intelligenza artificiale non possa sostituire il ruolo di uno psicoterapeuta o psichiatra specializzato, può rappresentare un valido supporto per comprendere meglio il paziente e ottimizzare il processo terapeutico.  

### **Obiettivo del progetto**  

L'obiettivo è sviluppare un'applicazione in grado di:  
- Trascrivere automaticamente le sessioni di psicoterapia a partire dalla registrazione audio.  
- Estrarre automaticamente note significative e valutare l'umore del paziente.  

### **Specifiche tecniche**  

L'applicazione accetterà in input un file audio e restituirà un file Markdown (.md) ben strutturato, contenente:  
1. **Nome del paziente**  
2. **Data e ora della sessione**  
3. **Umore del paziente**  
4. **Note della sessione**  
5. **Trascrizione completa**  

Il file dovrà essere salvato con il formato:  
`[Cognome-Nome]_[dd-mm-yyyy].md`  

**Nota:** Il nome del paziente e la data della sessione possono essere estratti direttamente dal file audio, in quanto vengono dichiarati dallo psicoterapeuta all’inizio della registrazione.  

### Restrizioni sul trattamento dei dati

Poiché i dati trattati rientrano nell’ambito medico, non è consentito l'uso di sistemi di intelligenza artificiale commerciali basati su API per il riconoscimento vocale (Speech-to-Text) o l'elaborazione del linguaggio naturale (LLM). È obbligatorio adottare soluzioni open-source che possano essere eseguite in locale o su server privati, garantendo il pieno controllo sui dati e il rispetto delle normative sulla privacy.

### I dati
[Registrazioni di sessioni di psicoterapia](https://proai-datasets.s3.eu-west-3.amazonaws.com/psychotherapy_sessions.zip)
