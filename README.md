# QBIKK for Mac

QBIKK er en Mac-app som tar opp møter og talenotater, transkriberer dem lokalt med NB-Whisper og gjør dem om til oppgaver, kalenderforslag og et minne om personer og prosjekter. Opptakene blir liggende på din Mac.

Dette repoet har bare ferdige versjoner av appen og oppdateringsstrømmen. Kildekoden ligger ikke her.

## Last ned

**[Last ned siste versjon (QBIKK.dmg)](https://github.com/martinnguyeen/qbikk-releases/releases/latest/download/QBIKK.dmg)**

Krever en Mac med Apple Silicon (M1 eller nyere) og macOS 14 eller nyere.

## Installer første gang

1. Åpne `QBIKK.dmg` og dra **QBIKK** til **Programmer**.
2. Åpne QBIKK. macOS stopper appen første gang, fordi den ikke er notarisert ennå.
3. Gå til **Systeminnstillinger ▸ Personvern og sikkerhet**, bla ned og trykk **Åpne likevel**.
4. Gi tilgang til mikrofonen når appen spør.

Dette trenger du bare å gjøre én gang. Etterpå oppdaterer QBIKK seg selv: når en ny versjon er lastet ned, står det «Ny versjon er klar» nederst i sidemenyen. Trykk **Installer og start på nytt** når det passer. Dataene og innstillingene dine blir som de er.

## Kom i gang

1. Gå gjennom introen (navn, rolle og hvordan du jobber).
2. **Settings ▸ Transcription:** installer **NB-Whisper Small** (ca. 0,5 GB).
3. **Settings ▸ Connections ▸ Google:** koble til kalenderen. Mens appen er i test, sier Google «Google hasn't verified this app». Trykk **Advanced ▸ Continue**. Martin må ha lagt deg til som testbruker først.
4. **Settings ▸ AI processing** (valgfritt): slå på og lim inn nøkkelen til NTNU IDUN. Dette virker bare på NTNU-nettet eller med VPN.
5. **Settings ▸ Connections ▸ Todoist** (valgfritt): lim inn API-tokenet ditt.
6. Trykk **⌥⇧R** for å starte og stoppe et opptak.

Spørsmål og tilbakemeldinger går direkte til Martin.

## Innhold i repoet

- `appcast.xml`: oppdateringsstrømmen appen leser (Sparkle, EdDSA-signerte arkiver)
- `notes/`: endringslogg for hver versjon
- [Releases](https://github.com/martinnguyeen/qbikk-releases/releases): `QBIKK.dmg` for første installasjon og `QBIKK-<versjon>.zip` for oppdateringer
