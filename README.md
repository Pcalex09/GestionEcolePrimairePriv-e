# Gestion Ecole Primaire Privee

Application JavaFX de gestion pour une ecole primaire privee.

## Stack

- Java 21
- JavaFX 21
- Maven

## Lancer le projet

Le Maven Wrapper permet de garder une execution identique entre les machines.

Linux / macOS :

```bash
./mvnw clean test
./mvnw javafx:run
```

Windows :

```bash
mvnw.cmd clean test
mvnw.cmd javafx:run
```

## Organisation

```text
src/main/java
  module-info.java
  com/ecole/App.java
  com/ecole/SystemInfo.java
```

`App.java` demarre l'application JavaFX.

`module-info.java` declare les modules necessaires au projet.

## Git

Les fichiers generes ou propres a l'IDE ne sont pas versionnes :

- `target/`
- `.idea/`
- `.m2/`
- `*.class`

Ces fichiers sont recrees localement par Maven ou par l'environnement de
developpement.
