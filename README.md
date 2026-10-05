# Carpentry Technical Output

Repository pubblico di **output tecnici da richiamare direttamente nelle task Notion** della falegnameria.

## Scopo

Qui vivono solo contenuti operativi e pubblicabili:
- disegni tecnici;
- schede di lavorazione;
- dime / coordinate;
- immagini di riferimento necessarie per eseguire una task.

Non devono essere caricati qui dati clienti, prezzi/margini interni, log gestionali o istruzioni agentiche.

La logica di processo, BOM, readiness e regole resta nel repository privato `falegnameria-management`.

## Indice macchina

- [index.yaml](index.yaml) — registro machine-readable degli output pubblici correnti.

## Albero di selezione

- [Wooden Dummy](wooden-dummy/README.md)
  - [Telaio](wooden-dummy/frame/README.md)
    - [Listelli flettenti](wooden-dummy/frame/flex-slats/README.md)
      - [LF-FORATURA-001 — Foratura listello flettente](wooden-dummy/frame/flex-slats/LF-FORATURA-001/README.md)

## Regole di pubblicazione

1. Ogni output tecnico ha un codice stabile, ad es. `LF-FORATURA-001`.
2. Le revisioni pubblicate non vengono sovrascritte silenziosamente: usare `revA`, `revB`, ecc.
3. Le task Notion devono puntare a una revisione esplicita.
4. Ogni cartella tecnica contiene almeno una specifica leggibile e il disegno operativo.
5. Il repository è pubblico: nessun contenuto sensibile.

## Convenzione percorsi

```
<prodotto>/<modulo>/<componente>/<codice-disegno>/
```

Esempio:

```
wooden-dummy/frame/flex-slats/LF-FORATURA-001/
```
