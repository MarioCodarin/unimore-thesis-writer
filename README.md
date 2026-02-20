# UNIMORE Thesis Writer

Plugin per Claude Code che scrive tesi di laurea per l'Università degli Studi di Modena e Reggio Emilia (UNIMORE).

## Cosa fa

- Scrive tesi seguendo le regole specifiche di ogni dipartimento UNIMORE (formattazione, lunghezza, struttura)
- Gestisce due sistemi di citazione: autore-data (APA) e note a piè di pagina
- Produce testo accademico naturale, come scritto da uno studente preparato (anti-pattern IA)
- Applica le norme ortografiche e tipografiche dell'italiano accademico
- Rispetta le policy UNIMORE su antiplagio, logo e deposito

## Dipartimenti supportati

1. Giurisprudenza
2. Economia "Marco Biagi"
3. Ingegneria "Enzo Ferrari" (DIEF)
4. Scienze Biomediche, Metaboliche e Neuroscienze (BMN) - Medicina
5. Comunicazione ed Economia (DCE) - Scienze della Comunicazione
6. Studi Linguistici e Culturali (DSLC)
7. Educazione e Scienze Umane (DESU)
8. Scienze Fisiche, Informatiche e Matematiche (FIM)
9. Scienze della Vita (DSV)
10. Scienze Chimiche e Geologiche (DSCG)
11. Scienze e Metodi dell'Ingegneria (DISMI)

## Come usarlo

La skill si attiva automaticamente quando chiedi a Claude Code di:
- "Scrivi un capitolo della mia tesi su..."
- "Aiutami con la tesi di laurea UNIMORE"
- "Formatta la bibliografia della tesi"
- "Scrivi l'introduzione della tesi"

## Struttura del plugin

```
unimore-thesis-writer/
├── .claude-plugin/
│   └── plugin.json
└── skills/
    └── thesis-writing/
        ├── SKILL.md                     # Prompt principale
        └── references/
            ├── department-rules.md      # Regole per dipartimento
            ├── citation-styles.md       # Sistemi di citazione
            ├── thesis-structure.md      # Struttura della tesi
            └── anti-ai-italian.md       # Pattern IA da evitare
```

## Installazione

Clona il repo direttamente nella cartella skills di Claude Code:

```bash
git clone https://github.com/mariocodarin/unimore-thesis-writer ~/.claude/skills/unimore-thesis-writer
```

Riavvia Claude Code — la skill è attiva automaticamente.

## Autore

Mario Codarin
