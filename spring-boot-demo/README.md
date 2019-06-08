# Simple Spring Boot REST application

## Run

Launch the application:
```sh 
mvn spring-boot:run
```

if you would like to obtain `100 Km` in  `Hm` :
```sh
curl 'http://localhost:8080/measurement/100/m/to/m?fromPrefix=KILO&toPrefix=HECTO'
```  

## Credits

This little demo was pair-programmed during meetup  `[Adopt-a-JSR Day] Adopt JSR 385 - Units of Measurement 2.0 for Java` by
Estêvão Hilst and Miguel Corrales.




