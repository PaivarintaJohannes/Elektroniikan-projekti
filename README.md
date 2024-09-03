# Elektroniikan sovellusprojekti 2024
Johannes Päivärinta, Samuli Pylkkönen

## Projektin tarkoitus oli sulautetun laitteen elektroniikan ja piirilevyn suunnittelu. 
Päätimme toteuttaa langattoman "sääaseman", laitteen joka mittaa lämpötilaa, ilmankosteutta jne ja toimittaa tiedot bluetoothin välityksellä puhelimeen. Laitteessa on lisäksi lcd-näyttö jossa näkyy samat arvot.
Prosessoriksi valittiin STM32WB55 joka pystyy bluetoothiin. Ohjelmointi ja debuggaus STM32CubeIDE:llä.
Onnistuin piirikaavion- ja levyn suunnittelussa ja komponentitkin saatiin tilattua ongelmitta. Komponenttien kiinnitys tehtiin itse. 
Tavoitteissa onnistuttiin vaikka lopulta ohjelmaa ei saatu ajettua levylle (prossu kärähti). Sama ohjelma laitettiin lopulta kehitysalustalle ja suunnitellut ominaisuudet bluetoothia lukuunottamatta toimi mainiosti. Kehitysalusta ei tukenut bluetoothia joten siitä oli luovuttava.

## Piirikaavio
![piirikaavio](https://github.com/PaivarintaJohannes/Elektroniikan-projekti/blob/main/piirikaavio.png)

## Valmis levy
![valmis levy](https://github.com/PaivarintaJohannes/Elektroniikan-projekti/blob/main/piirilevy.png)

## Kehitysalusta
![valmis levy](https://github.com/PaivarintaJohannes/Elektroniikan-projekti/blob/main/kehitysalusta.png)
