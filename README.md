# Calculator Example 1.2 

Upgraded, tested and cleaned for Continuous Delivery Pipeline testing

## Installation

no special installation needed, currently upgraded Tools Version for 1.2
- Maven 3.8.6
- JDK 19.0.1

```bash
mvn clean
```

## Usage

```bash
mvn test
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)

(optional) Überlegen Sie sich, wie Sie die einzelnen Schritte (compile und test) separat als 
steps abbilden können. Wäre das vorteilhaft? Begründen Sie Ihre Antwort.

A: Ja würde vorteilhaft sein bei größeren Porjekten, bei einem kleinen Projekt würde es unnötig sein. Durch die aufteilung können einzelne steps aufgeteilt werden und klarer ersichtlich.

 Wann können Workflows ausgelöst werden? 

A: Grundsätzlich immer und wenn dies sinn ergeben

 Wann macht es in einem Projekt Sinn einen Workflow auszulösen?

A: Bei einem event, pull, push, pull-request, commit, ...

 Welche Schritte sind für Ihr Projekt automatisierbar?

A: Ebenfalls grundsätzliches kann man alles automatisieren.

 Wie sind Workflows grundlegend aufgebaut?

A: Event -> steps -> befehle, ausgabe, ...

 Wozu dienen unterschiedliche Runner (Betriebssysteme) in GitHub Actions?

A: Man kann mehrere Runner nutzen um gewisse steps und events aufzuteilen bzw. kann man einzelne Runner auch User zuweisen

 Wie können auch unterschiedliche Versionen, zB Java mittels Workflows automatisiert 
getestet werden? (Stichwort: Matrix Strategy)

A: Durch die Nutzung von einer Matrix diese ermoglicht die Nutzung von verschiedenen Versionen und damit können Workflows automatisiert werden
