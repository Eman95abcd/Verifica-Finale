# Spiegazione del codice usato per la creazione del database "compagni" e della tabella "compagni"


## Creazione database "compagni"  


1. Creazione database 'compagni.db'con seguente script:

```
sqlite3 compagni.db;
```

## Creazione tabella "compagni"


2. Creazione tabella 'compagni' con seguente script: 

```
create table compagni(nome text, cognome text, email text);
```

## Inserimento dati nelle relative colonne(nome, cognome, email)

3. Inserimento dati con seguente script:

```
insert into compagni(nome, cognome, email) values ('nome', 'cognome', 'email');
```


