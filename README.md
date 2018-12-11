# HTW_WIW_WS1819_MLProject

Im Rahmen eines WIW-Projekts zum Thema Predictive Maintenance an der HTW Berlin) wurde eine Gruppe von Studenten in zwei Teams unterteilt: Team Prediction und Team App. Ersteres war dafür zuständig, Maschinendaten zu simulieren und mittels ML-Methoden zu analysieren. Für die Visualisierung in einer App, wurden die Simulations- und Analysedaten dem App Team per Datenbanken zur Verfügung gestellt. 

 
Abbildung 1: Teamaufteilung Predictive Maintenance

Die entwickelten Codes des Teams Prediction können verwendet werden, um die Simulation und ML-Analysen im eigenen Programm live zu nehmen.

## Codes

### Simulation
Um Analysen nach ML-Methoden durchführen zu können, müssen vorab Maschinendaten simuliert werden. Hierfür können mit dem Code zur Simulation kontinuierlich (alle 30 Sekunden) per Zufallsgenerator Daten zu folgenden Maschinenparametern erstellt werden:
-	Drehzahl,
-	Leistungsaufnahme,
-	Vibration,
-	Lautstärke,
-	Temperatur,
-	Fehler ID,
-	Produktionsprogramm,
-	Ist-Menge.

### Analysen
Die aus der Simulation gewonnenen Maschinendaten können mit verschiedenen Codes analysiert werden. Dabei werden folgende ML-Methoden verwendet:
-	Lineare Regression,
-	ARIMA.

## Datenbanken

Sowohl die Simulationsdaten, als auch die Analysedaten werden kontinuierlich in SQL-Datenbanken übertragen, welche auf einem Server der HTW Berlin zur Verfügung gestellt wurden. Somit stehen die Daten für das App Team bereit zur Visualisierung. 













# HTW_WIW_WS1819_MLProject

Projekt Description

## Installing

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc


## Contact Information
