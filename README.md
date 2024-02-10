# FacialEmotionsRecognitionsUsingComputerVision
## Prikaz rada aplikacije
Na narednim slikam moguće je videti način rada apikacije. Za potrebe diplomskog rada, radili smo prepoznavanje i analizu emocija na video snimku na kome se nalaze studenti u učionici koji čekaju usmeni deo ispita. Sam rad aplikacije se može podeliti na 2 dela.
1. Prepoznavanje  i detekcija lica - korišćen je DNN iz OpenCV biblioteke
2. Prepoznavanje i klasifikacija emocija - korišćena je  naša pretrenirana neuronska mreža
Kao što je i moguće videti u nastavku, imamo da se najpre detektuju lica, pri čemu sistem svako detektovano lice označava  zelenom pravougaonom oblašču, a nakon toga se iznad pravougaonika ispisuje emocija koju je sistem detektovao, odnosno prepoznao kao takvu.
