# GIT-TEST
## ALE ACAMPORA

Questa repo è stata creata per fare testing e prova di comandi git e git flow.

> "Carino git e git flow"

***
<br>
<br>

# Modifica con GIT FLOW

Git è uno strumento per il controllo delle versioni che traccia le modifiche ai file nel tempo, agevolando la collaborazione su progetti software. Permette di registrare le modifiche con "commit", sviluppare nuove funzionalità in "branch" separati e unire le modifiche in modo ordinato.

***
<br>
<br>

# STEP PER FARE UNA FEATURE CON GIT FLOW
```git 
1. INIZIA LA FEATURE: git flow feature start "nome_feature"
2. restyling del file, codice (ecc...)
3. git add -A 
4. fai un commit (git commit -m ...)
5. FINISCE LA FEATURE: git flow feature finish "nome_feature"
```

# Una volta fatta la feature, fare la release con la versione (ex v0.0.1...)
```git 
1. INIZIA LA RELEASE: git flow release start 0.0.0 (es)
2. FINISCE LA RELEASE: git flow release finish '0.0.0'
```

# Fatta la release con la versione, "pushare" tutto al server.
```git 
1. git push
```

# MODIFICA CON LA TERZA FEATURE
Va bene così.