# Detect_Foot
 "detectfoot_bothCamera" è un software utilizzato per rilevare i piedi dei robot NAO, in immagini scattate durante la competizione RoboCup SPL. Le immagini fornite sono frame di video registrati durante le partite di calcio, sia dalla upper camera sia dalla lower camera. 

### Prerequisites

You need to have OpenCV 4.3 installed to compile and run the code

### Build the code

```
mkdir build
cd build && cmake ..
make
```

### Run the code

```
detectball test
```

where test is a folder containing images.

### Examples

![detectball-examples](./images/detectball-examples.png)

Please, report bugs to domenico.bloisi@gmail.com
