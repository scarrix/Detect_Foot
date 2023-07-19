# Detect_Foot
detectfoot_bothCamera è un software utilizzato per rilevare i piedi dei robot NAO, in immagini scattate durante la competizione RoboCup SPL. Le immagini fornite dai dataset sono frame di video registrati durante le partite di calcio, sia dalla upper camera sia dalla lower camera. 

## Prerequisiti
E' necessario aver installato e settato correttamente OpenCV 4.3 per eseguire l'applicazione.

## Compile & Build
Per compilare il sorgente usiamo il CMakeLists, mediante Visual Studio. Creiamo i file di build in una cartella appositamente creata, aprendo il terminale, posizionandoci nella radice del progetto ed eseguendo i comandi
```
mkdir build
cd build && cmake ..
make
```
Successivamente generiamo l'eseguibile compilando con Visual Studio.

## Esecuzione codice
Il comando di esecuzione del software
```
detectfoot.exe path\to\test
```
esegue il detection dei piedi dei robot NAO sulle immagini presenti nella cartella test. Nel momento in cui riconosce una caratteristica nota (il piede di un robot NAO) il software circoscrive la zona rilevata mettendola in evidenza. 
