# Codice Fox
Codice Fox è un codice basato su PHP 7.2 per iniziare a programmare in PHP

## Installazione
Per installare il Codice Fox è necessario avere installato PHP 7.2<br>
Installamo PHP 7.2: `apt install php7.2-fpm`<br>
Ora scarichiamo il file install.sh per installare il tutto dalla pagina dei relase<br>
Eseguiamo **install.sh** con il comando `sh install.sh`<br>
Il sistema ci chiederà la directory di installazione, consigliamo la cartella `/var/www`

## Chiamare il Codice Fox
Per chiamare il Codice Fox in una pagina php basterà mettere
```php
<?php
// Supponiamo che siamo nella cartella /var/www/ciao e che il Codice Fox sia in /var/www/cfox/
include("../cfox/loader.php");
$lettura = function leggi("ciao");

echo "Dentro il file ciao c'è scritto $lettura";
?>
```


## Sinstassi di Codice Fox
Codice Fox possiede una sintassi particolare sottoforma di **funzioni**
Per chiamare una funzionalità basterà fare `function leggi("ciao");`

## Assistenza
Potrai richiedere supporto per il Codice Fox in qualsiasi momento contattando **FoxWorn3365#6736** su Discord oppure **@FoxWorn3365** su Telegram

## I Vantaggi di Codice Fox
Codice Fox possiede tutte le funzionalità (o almeno quasi tutte) sottoforma di funzioni in italiano.
Ne ricordiamo qualcuna:
```
- leggi
- scrivi
- vuoto
- crea
```
 
 ## Come chiamare una Variabile
 Per chiamare una variabile sarà necessarip fare semplicemente
 ```php
 function scrivi("ciao", "contenuto del file", "+w");
 ```

## Consulta la nostra Wiki
Consulta ora la nostra wiki che trovi nel menu del reposity di Codice Fox
