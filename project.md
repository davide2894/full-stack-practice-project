# Macro-fasi in cui dividere il progetto

1. caratteristiche funzionali UX
2. caratteristiche tecniche cioè dell'applicativo
   - design patter da seguire?
   - full stack unico o progetti separati?
   - cosa farà
   - web app? mobile app?
   - front?
   - full?
   - stack?
   - test unitari
   - test automatici
   - DB
     - come strutturarlo?
     - SQL?
     - Mongo
3. processo di sviluppo
4. branch flow
5. convenzioni di sviluppo:
   - case file
   - case cartelle

## caratteristiche funzionali UX

- 1 sola pagina
- landing -> mock1
- scelta:
  - serie tv o film?
  - genere
- tasto choose

Flusso:

1. user fa la prima selezione:
   - movie
   - serie tv
2. user sceglie uno a più generi
3. user clicca choose btn
4. random video viene scelto
5. user può mettere like o dislike:
   1. dislkike max tre volte
      -> se si arriva alla quarta scelta\_
      -> non c'è più possibilità di scelta
   2. se like --> tutti felici

## caratteristiche tecniche cioè dell'applicativo

- design patter da seguire -> MVC
- web app
- full stack
- test
  1. front-end: e2e
  2. back-end: unit test
- DB
  - come strutturarlo?
  - SQL
- progetto unico o progetti separati?
