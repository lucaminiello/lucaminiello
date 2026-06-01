# Installazione — Luca Miniello AI Profile OS V4

Questa versione è stata ricostruita da zero.

## Cosa devi caricare nel repo

Nel repository `lucaminiello/lucaminiello` devi avere questa struttura:

```txt
README.MD
assets/
.github/workflows/snake.yml
```

## Metodo consigliato: GitHub Desktop

1. Scarica lo ZIP `lucaminiello_AI_PROFILE_OS_ZERO_V4_UPLOAD_READY.zip`.
2. Estrai lo ZIP sul computer.
3. Apri GitHub Desktop.
4. Clona il repo `lucaminiello/lucaminiello`.
5. Apri la cartella locale del repo.
6. Cancella il contenuto vecchio del repo.
7. Copia dentro i nuovi elementi:

```txt
README.MD
assets/
.github/
```

8. Torna su GitHub Desktop.
9. Scrivi come messaggio commit:

```txt
Replace profile with AI Profile OS V4
```

10. Clicca `Commit to main`.
11. Clicca `Push origin`.

## Attivare la snake animation

1. Vai su GitHub nel repo `lucaminiello/lucaminiello`.
2. Apri la tab `Actions`.
3. Se richiesto, abilita i workflow.
4. Apri `Generate Contribution Snake`.
5. Clicca `Run workflow`.
6. Dopo il primo run verrà creato il branch `output` con lo SVG della snake.

## Errori comuni

### Le immagini non si vedono
Controlla che la cartella si chiami esattamente:

```txt
assets
```

Non `asset`, non `images`, non `img`.

### Il profilo non si aggiorna
Controlla che il file sia nella root del repo:

```txt
README.MD
```

Non deve essere dentro una sottocartella.

### La snake non si vede
È normale finché non lanci il workflow almeno una volta dalla tab Actions.
