# SW Design Principles
Software design principles

## SOLID

Robert C. Marting som introduserte SOLID

Gode hint, tanker å ha med seg når man lager software. (Litt som veiskilt)

Veien til å unngå:
- kode som knekker lett
- vanskelig å gjøre en endring uten å påvirke mye annen kode
- kode som er vanskelig å gjenbruke

### (SRP) Single Responsibility
 - samle ting som endrer seg av samme grunn, spre ting som endrer seg av forskjellig grunn

 // filer
 // klasser
 // funksjoner/componenter
 // større design elementer kompositt strukturer
 // utskrift/error handling isteden for at hver metode skal gjøre (error handling -> trekke ut å sentralisere)
 ```js

    const Saksdokumenter = () => {
        return 2;
    }

 ```



### (OPC) Open/Closed


### (LSP) Liskov Substitution


### (ISP) Interface Segregation


### (DIP) Dependency Inversion