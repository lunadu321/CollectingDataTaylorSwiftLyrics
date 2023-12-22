# CollectingDataTaylorSwiftLyricsCorpus
This is an assignment for Collecting Data.

## Corpus Description

The Taylor Swift Songs' Lyrics Corpus is a collection of text files, each containing the lyrics of one song by Taylor Swift from her 2023 album "Midnights (The Till Dawn Edition)". The corpus is intended for use in natural language processing (NLP) and text analysis tasks. 

## Target Audience and Intended Use

The target audience for this corpus includes researchers in NLP, linguistics, and music analysis, as well as data scientists interested in text-based analysis. The potential use of the corpus is to enable investigations into language patterns, sentiment analysis, and other text-related studies within the domain of Taylor Swift's song lyrics.

## Text Selection Criteria

The songs included in this corpus are solely from Taylor Swift's 2023 album "Midnights (The Till Dawn Edition)", which is her latest album.

## Data Collection Process

The data in each text file is collected by copying and pasting the lyrics of her songs. These text files were then organized into a clear structure, and the corpus was constructed based on these files.

## Annotations and Tools

The primary annotations in the corpus are tokens, lemmas, and parts-of-speech, added using the spaCy library. No additional annotations or metadata beyond the song titles and lyrics were included.

## File Formats

- **Text Files (.txt):** Individual text files for each song containing the lyrics.
- **CSV File (annotated_corpus.csv):** A CSV file containing the annotated corpus data with the following columns:
  - **Filename:** The name of the original text file.
  - **Title:** The title of the song.
  - **Document:** The original text exactly as it appears in the text file.
  - **Tokens:** Tokenized text of the document.
  - **Lemmas:** Lemmatized text of the document.
  - **Parts-of-speech:** Parts of speech of all the tokens in the document.


