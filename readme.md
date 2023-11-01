# Classical Music Chord Corpus
- With annotated start and end tags

## Datasets

This corpus provides two different forms of data, the first is the chords shown as a list of notes. The second is the chords shown as a list of scale degrees.



### Chords as Note Names

Each note takes the form of:

`C(#/-)4`

Where C is the note name, (#/-) is an optional sharp/flat, and 4 is the octave.

Start and end are annotated with `START` and `END` respectively.

### Chords as Scale Degrees

Each note takes the form of:

`[0-11]`

Where 0 is the tonic and 11 is the subtonic.

Start and end are annotates with `999` and `-1` respectively.

## Files

| Name | File |
|------|------|
|Chords as Note Names | [chords.txt](./data/chords.txt) |
|Chords as Scale Degrees | [degrees.txt](./data/degrees.txt) |


## Source Information

Composers Included:
- Telemann
- Schumann
- Tchaikovsky
- Mendelssohn
- Byrd
- Scarlatti
- Chopin
- Debussy
- Mozart
- Saint-Saens
- Handel
- Beethoven
- Liszt
- Bach
- Brahms
- Wagner
- Schubert
- Vivaldi
- Haydn

Data was sourced from the [Yale Classical Archives Corpus](https://ycac.yale.edu/)