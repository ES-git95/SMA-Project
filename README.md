# SMA-Project

This is the final project of the Social Media Analytics of Univeristà degli Studi di Milano - Bicocca.

The scope of the project is.....

Antivax VS Provax
Analisi dei tweet attraverso uno o più hashtag specifici per l'identificazione di cluster pro o anti vax. Studio dei cluster e della loro influenza sul dibattito social.

- Creazione rete e cluster solo con i retweet (NB!! utilizzando come nodi i nomi utente e non i tweet: x ha ritwittato y) 
- Aggiunta alla rete di risposte e menzioni per analizzare come interagiscono tra loro i cluster (la rete sarà visualizzata con cluster colorati diversamente con risposte e menzioni di colore neutro)
- Caratteristiche cluster: sentiment analysis, word cloud (analisi da fare solo sui cluster perché saranno caratterizzati allo stesso modo, le risposte e menzioni potrebbero avere posizioni differenti al cluster a cui si riferiscono/rispondono) 
- Esiste un ingerenza esterna ad influenzare l'opinione sui social? Bot detection, distribuzione account per giorni dalla data di creazione rispetto al cluster

To do:
1. Aggiungere colonna delle menzioni (se il tweet è rivolto a qualcuno ma non è una risposta)
2. Creazione rete dei retweet
3. Community detection (Scelta algoritmo, metodo gerarchico con utilizzo di legame singolo?)
4. Aggiunta di risposte e menzioni alla rete
5. Analisi della nuova rete (Centrality, Closeness centrality, Betweenness centrality, Delta centrality, Density, Cohesion, Count of cliche & social circles)


