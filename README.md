# Geometria e Algebra Lineare

Cheatscheets per l'esame di Geometria e Algebra Lineare.

## Files

- `geometria1`: primo parziale
- `geometria2`: secondo parziale

## Compilazione

### Requisiti

- `pdflatex`
- `latexmk`

### Compilazione

- `latexmk` nella root del repo per compilare `geometria1` e `geometria2`
- `latexmk -pvc file.tex` per compilare on-the-fly ad ogni salvataggio (meglio se il pdf è già aperto nel viewer)
- `latexmk -c` per rimuovere i file junk
- `latexmk -C` per rimuovere tutti i file generati