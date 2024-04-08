# Progetto WIP con soglie di immissioni e prelievi configurabili

# Node-RED-fv-air-conditioner-heating

Il seguente flusso NodeRed permette di massimizzare l'autoconsumo fotovoltaico per scaldare casa attraverso dei condizionatori smart con pompa di calore.
N.B. il flusso si basa su entity esposte da Home Assistant

La lettura dei prelievi ed immissioni in rete è stata realizzzata attraverso la creazione di 2 sensori diversi in Home Assistant, i quali prelevano il medesimo valore da uno shelly EM con TA fissato sul cavo che dal contatore del distributore giunge al quadro domestico.
I condizionatori utilizzati sono dei Samsung integrati in Home Assistant.
