# Technikum Technologii Cyfrowych - Strona Internetowa

Responsywna strona one-page dla Technikum Technologii Cyfrowych.

## Uruchomienie za pomocą Dockera

### Wymagania
- Docker
- Docker Compose

### Instalacja i uruchomienie

1. Sklonuj repozytorium:
```
git clone <adres-repozytorium>
cd ttc
```

2. Zbuduj i uruchom kontener:
```
docker-compose up -d
```

3. Strona będzie dostępna pod adresem http://localhost:8080

### Uruchomienie w trybie deweloperskim

Dla trybu deweloperskiego z automatycznym odświeżaniem zmian:

```
docker-compose -f docker-compose.yml -f docker-compose.dev.yml up
```

### Zatrzymanie kontenerów

```
docker-compose down
```

## Struktura projektu

- `index.html` - główny plik HTML strony
- `css/` - pliki CSS
- `js/` - pliki JavaScript
- `images/` - obrazy i grafiki

## Licencja

Ten projekt jest dostępny na licencji MIT.
# ttc
