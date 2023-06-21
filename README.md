# pr8-week7-train-her
herkansing van weekopdracht 7 (train) van programmeren 8

Welke CSV file heb je gebruikt? Is deze geschikt voor regression? Welke waarde ga je voorspellen?
ik heb de winequality CSV gebruikt, deze is geschikt voor regression omdat de dataset bevat verschillende kenmerken, zoals "fixed acidity," "volatile acidity," "citric acid," enzovoort, die als variabelen kunnen worden gebruikt voor het voorspellen van verschillende zaken. ik wil graag de qualiteit van deze wine voorspellen.

Heb je een scatterplot gemaakt van je data? Waarom wel of niet?
Nee ik heb geen scatterplot gemaakt, de reden hiervoor is dat de dataset zo groot was dat ik bang zou zijn dat de scatterplot onoverzichtelijk kunnen maken waardoor ik er uiteindelijk toch niks aan zou hebben.

Welke kolommen uit je data heb je gebruikt voor het trainen van je model?
fixed acidity, volatile acidity, citric acid, chlorides, free sulfur dioxide, total sulfur dioxide, sulphates, alcohol

Hoe heb je de data voorbereid voordat je bent begonnen met trainen?
De CSV-data wordt geladen met behulp van de Papa Parse
De data wordt willekeurig gesorteerd met behulp van de sort-functie
De data wordt verdeeld in trainingsdata en testdata.

Kon je een neural network trainen? Hoeveel epochs heb je gebruikt? Heb je het aantal epochs aangepast?
ja het is mij met deze code gelukt om het network te trainen, doormiddel van de train methode. ik heb gebruik gemaakt van 32 epochs

Heb je het model kunnen opslaan en inladen in een nieuwe HTML pagina? Wat is het nut van het opslaan van het model?
Ja het is mij gelukt om het model op te slaan en in te laden in een apparte HTML pagina. Je wil je model graag opslaan zodat je bij ieder nieuw gebruik van je model deze niet weer eerst hoeft te trainen voordat je deze weer kan gaan gebruiken. als je je model opslaat kan je deze direct weer gebruiken.
