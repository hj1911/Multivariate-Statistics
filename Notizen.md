# Notizen

## 29.10.24
- Achtung bei Paketen von R, nicht alle Pakete noch aktuell, da nicht mehr daran gearbeitet
- Installieren von Paketen über Befehl(siehe unten) oder über Tools

`dependencies` bei **Installieren von Paketen**, um abhängige Pakete ebenfalls zu installieren:
```r
install.packages("foreign", dependencies = TRUE)
```

**Laden von Paketen:** 
```r
library("foreign")
```

**Nützliche Funktionen:**
- `View(df)`-> Datensatz aufrufen
- `head(df)`-> head ausgeben
- `names(df)`-> Variablennamen
- `ncol()`-> Anzahl Spalten
- `nrow()`-> Anzahl Zeilen
- `dim()`-> Anzahl Spalten und Zeilen
- `summary()`,`describe()`-> einfache Zusammenfassung/Beschreibung des Datensatzes

## 30.10.24
- Variablen recodieren mit `car::recode()` oder Wertezuweisung oder Addition/Subtraktion
- Stuktur eines Objektes anschauen mit `str()`
- direktes Ausgeben einer Variable mit Klammer, z.B.: `(a<-b+c)`
- Faktoren definieren mit `as.factor()`
