# Progetto AML
## Previsione della durata delle corse dei taxi con approccio basato su deep learning


Pietro Colombo - 793679 - p.colombo45@campus.unimib.it

Carlo Radice - 807159 - c.radice@campus.unimib.it

Marco Fagioli - 808176 - m.fagioli2@campus.unimib.it

Ordine di esecuzione degli script:

### ***1 - Analisi e integrazione datasets con clustering.ipynb***
Scarica i dataset da http://kaggle.com, crea in output:

*data_weather_osm.csv*

*test_weather_osm.csv*

### ***2 - Preprocessing.ipynb***
Prende in input il csv *data_weather_osm.csv* e crea in output:

*output_preprocessing.csv*

### ***3 - Hyperas A.ipynb***
Utilizza Hyperas per ottimizzare gli iperparametri

### ***4 - Neural network.ipynb***
La rete migliore trovata con Hyperas viene usata per predire sul dataset di test per confrontarci su kaggle 

*neural_submission.csv*
