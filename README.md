# Esercizio
Organigramma dei dipendenti di un'azienda.


## Descrizione
- reparto management
   - direttore
   - assistente direttore
- reparto vendite
   - dipendenti (nome,cognome)
- reparto contabilità
   - dipendenti (nome,cognome)
- reparto servizio clienti
   - dipendenti (nome,cognome)
- reparto magazzino
   - dipendenti (nome,cognome)

## Codifica
```js
const orgAzienda = {

    repartoManagement: {
        direttore: {
            nome: "Michele",
            cognome: "Scotti"
        },
        assitenteDirettore: {
            nome: "Davide",
            cognome: "Strutto"
        }
    }, repartoVendite: {
        dipendenti: [
            { nome: "Jim", cognome: "Alberti" },
            { nome: "Andrea", cognome: "Bernardi" },
            { nome: "Pamela", cognome: "Bestli" }
        ]

    }, repartoContabilità: {
        dipendenti: [
            { nome: "Angela", cognome: "Martini" },
            { nome: "Oscar", cognome: "Martino" }

        ]

    }, repartoServizioClienti: {
        dipendenti: [
            { nome: "Kelly", cognome: "Capura" }
        ]


    }, repartoMagazzino: {
        dipendenti: [
            { nome: "Rosario", cognome: "Adersoni" },
            { nome: "Danilo", cognome: "Fiblino" }

        ]

    }
};

```