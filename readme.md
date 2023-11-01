# The Classical Music Chord Corpus
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

Start and end are annotated with `999` and `-1` respectively.

## Files

Both files come as 

| Name | File | Compressed Size | Uncompressed Size |
|------|------|-----------------|-------------------|
|Chords as Note Names | [chords.zip](./data/chords.zip) | 5.7mb | 39.9mb |
|Chords as Scale Degrees | [degrees.zip](./data/degrees.zip) | 14.1mb | 90.4mb |

## Data Sample

| Names | Degrees|
|-------|--------|
| START | 999 |
| G5 E-5 G4 C5 C4 | 0 3 7 |
| G5 G4 C5 E-5 C4 | 0 3 7 |
| G#5 G4 C5 E-5 C4 | 7 8 0 3 |
| G5 C5 G4 E-5 C4 | 0 3 7 |
| G5 E-5 G4 C5 C4 | 0 3 7 |
| G4 C5 E-5 C4 | 0 3 7 |
| D5 | 2 |
| C5 | 0 |
| G5 D5 D4 G4 B3 | 7 11 2 |


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
