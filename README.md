# PONICA
coltura idroponica domotica Majorana

MANUTENZIONE:
-
La centralina "PonicStation R1" non ha bisogno di particolari manutenzioni.
Ci sono però delle accortezze da tenere:
  - l'unica componente della centralina che può entrare a contatto con l'acqua è la pompa.
  - la centralina consuma una quantità di elettricità minima, però se venisse cambiato il sistema di alimentazione allora andrebbe calibrata la luminosità (vedi dopo)
  - deve essere alimentata ad un tensione di corrente di 5V, ad esempio collegandola ad un PC, ad un powerbank o semplicemente ad un caricabatterie utilizzato comunemente per i telefoni


SENSORI E MODULI:
  -
  -  Modulo con sensore DTH11
  -  Modulo KY-018 con fotoresistenza
  -  Schermo LCD 128x64 con microcontrollore ST7920
  -  Scheda KEYESTUIDO Mega 2560 Plus (una scheda clone della scheda Arduino Mega 2560. in aggiunta questa scheda scelta ha var slot per il collegamento più semplice dei sensori)


FILE ED UTILIZZI:

LumTempUmidSeriale --> Serve a testare i sensori di luminosità (KY-018) e di temperatura ed umidità (DHT11)
                       il codice va caricato sull'IDE di arduino e vanno fatti questi collegamenti
                       DTH11: 
                               "-" GROUND
                               "+" 5V
                               
