Progetto Basi di dati II
=======================

Il progetto è stato realizzato per l'esame di basi di dati 2.
Il lavoro è stato realizzato in collaborazione con il Professor Frank Marzano e l'Ingegnere Mario Montopoli, 
i quali hanno fornito un campione di dati pluviometrici della provincia del Lazio (realativi ad 1 mese ).

I principali strumenti utilizzati sono stati R, PostgreSQL, PostGIS, QuantumGIS.

Il caso di studio illustrato riguarda l’analisi approfondita di dati pluviometrici reali, contenuti in alcuni file idrografici forniti dal prof. Frank Marzano e dall’ing Mario Montopoli, riguardanti un arco temporale relativamente piccolo e relativi ad alcuni pluviometri del centro italia.
Il primo passo è stato quello di salvare questi dati in un database spaziale e di filtrarli in modo da eliminare quelli che potevano essere dati non congrui alla realtà. In seguito è stata avviata una fase di analisi geostatistica dei dati. 
Di seguito vengono elencati i tre distinti casi di analisi:

•	Generazione di tabelle e di grafici che rendono i dati più comprensibili e permettono di visualizzare graficamente l'andamento delle precipitazioni;

•	Studio di un’applicazione GIS open source (QGIS) al fine di creare nuovi progetti di mappe contenenti vettori di punti relativi ai pluviometri e ai dati prelevati dal DB direttamente dall’interfaccia grafica del programma, visualizzare mappe vettoriali e raster, e sfruttare plug-in appositi per compiere analisi spaziali;

•	Utilizzo di tecniche geostatistiche per interpolare spazialmente i dati pluviometrici.

E’ bene rimarcare che la finalità primaria del progetto non è solo quella di creare mappe o grafici da offrire a coloro che dovranno agire in concreto sui dati archiviati, oppure di fornire indicazioni su come implementare un DB spaziale in cui raccogliere dati pluviometrici, come detto in precedenza, ma anche quella di fornire un metodo di analisi dei dati pluviometrici differente rispetto ad altri lavori e/o progetti di studio dei campi di precipitazione. In particolare il nostro lavoro permette, tramite l’utilizzo di software open source integrabili tra di loro, di raggiungere risultati ottimi e facilmente comparabili con altri lavori e/o pubblicazioni scientifiche che per la maggior parte dei casi utilizzano strumenti software proprietari.

