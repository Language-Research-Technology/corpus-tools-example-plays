# corpus-tools-example-plays
A collection of plays from the 1500's in TEI XML as an example of using spreadsheets to load data into and Arkisto repository (RO-Crate in OCFL served by Oni)

(This is incomplete -- full instructions coming ASAP but see this [presentation](https://github.com/Language-Research-Technology/qa/raw/main/presentations/oni-dev-track-OR-23/2023-06-13-sefton-introducing-the-oni-stack.pptx))


## To install stuff and get started

npm install 
Make an RO-Crate from the data that's here:

`
rocxl -d 3 -m 305 .
`
Rename the resulting ro-crate-metadata spreadsheet

`
rocxl 
`


Split Author column on 'and', '&' into multiple new columns


