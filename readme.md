# Configurazione di base Vercel su Heroku
Configurazione iniziale per sviluppare App con Vercel per poi distribuirla su Heroku

## Premessa

Installare Parcel non come sviluppo (--save-dev) ma semplicemente in locale (--save), salvo non l'hai installato globalmente in quanto va benissimo!
Questo perchè Heroku avrebbe problemi nel trovare Parcel lato sviluppo.

### Registrazione sul sito di Heroku e installare il client di heroku sullaa propria macchina

https://www.heroku.com 

### Loggarmi inserendo le credenziali

$ cd [ my_app ]

$ heroku login

### Creare nuova repository remota su Heroku

$ heroku create

( $ heroku create -b [ link repository esistente su Heroku ] )

### Deploy su Heroku

$ git add .

$ git commit -m "deploy on heroku"

$ git push heroku master

### Aprire il progetto su browser

$ heroku open

### Visita l'app deployata

https://vast-retreat-72309.herokuapp.com/

#### Enjoy development! ;-)
