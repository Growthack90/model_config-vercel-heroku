# Configurazione di base Vercel su Heroku
Configurazione iniziale per sviluppare App con Vercel per poi distribuirla su Heroku

## Premessa

Installare Parcel non come sviluppo (--save-dev) ma semplicemente in locale (--save), salvo non l'hai installato globalmente in quanto va benissimo!
Questo perchè Heroku avrebbe problemi nel trovare Parcel lato sviluppo.

### Step 1 - Registrazione sul sito di Heroku e installare il client di heroku sullaa propria macchina

https://www.heroku.com 

### Step 2 - Loggarmi inserendo le credenziali

`$ cd [ my_app ]`

`$ heroku login`

### Step 3 - Creare nuova repository remota su Heroku

`$ heroku create`

( `$ heroku create -b [ link repository esistente su Heroku ]` )

### Step 4 - Deploy su Heroku

`$ git add .`

`$ git commit -m "deploy on heroku"`

`$ git push heroku master`

### Step 5 - Aprire il progetto su browser

`$ heroku open`

### Se riporto modifiche locali al codice ripetere Step 4 e 5

### Visita l'app deployata

https://vast-retreat-72309.herokuapp.com/

#### Enjoy development! ;-)
