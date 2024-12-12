# <a href="https://www.yiddishcorpus.org"><img alt="CSYE logo" src="https://www.yiddishcorpus.org/csye/assets/img/logo/CSYE-logo.svg" width="75px" /></a> CSYE Transcripts

This public repository hosts all of the testimony transcript files that are available as part of the [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org) (קאָרפּוס פֿון דער ייִדישער שמועסשפּראַך אין אײראָפּע).
New transcripts are being added all the time, so please check back for the latest additions.

As a reminder, the use of all CSYE materials, including these transcripts, is governed by our Terms of Use and requirements for proper attribution in citations, provided [here](https://www.yiddishcorpus.org/csye/user-guide/).

## Download the transcripts

To save the transcripts for offline use, you can either [download a ZIP of the repository here](https://github.com/YiddishCorpus/CSYE-Transcripts/archive/main.zip) or, if you prefer to use the command line:

    wget https://github.com/YiddishCorpus/CSYE-Transcripts/archive/main.zip -O CSYE-Transcripts-main.zip

## Repository structure

Transcripts are available in several different formats, each in its own directory:
* `txt/`: Text files where each line contains (tab-separated): the name of the speaker, the start time of the utterance (seconds), the end time of the utterance (seconds), and the content of the utterance
* `eaf/`: Transcript files that can be opened in [ELAN](https://archive.mpi.nl/tla/elan), with a separate tier for each speaker
* `TextGrid/`: Transcript files that can be opened in [Praat](https://www.fon.hum.uva.nl/praat/), with a separate tier for each speaker

There are also directories containing the transcripts in subtitle format (`srt/`, `vtt/`), which we use to embed subtitles in the videos displayed on the corpus website. We do not recommend using these because they are not as informative as the other formats (they do not include speaker names or tiers, certain disfluencies, etc.).

Within each of the directories for file formats, you will find `reviewed/` and `unreviewed/` subdirectories. Transcripts that have been "reviewed" have been checked by a CSYE team member who was not the original transcriber, and these are available in both Latin transliteration (`la`) and the Hebrew-based Yiddish alphabet (`he`). "Unreviewed" transcripts are available only in Latin transliteration.

## Submitting corrections

If you notice any typographical errors or mistranscriptions,[^1] in either orthography, we encourage you to submit corrections to our team by [opening a support ticket](https://github.com/YiddishCorpus/CSYE-Transcripts/issues/new?assignees=ibleaman&labels=correction&template=CORRECTION_REPORT.yml&title=%E2%9C%8F%EF%B8%8F+%5BCORRECTION%5D+-+%3Ctitle%3E), which we can track and resolve. Before doing so, make sure that you have [created a GitHub account](https://github.com/join) and are signed in.

[^1]: `UNK` and angle brackets `<...>` appear in transcripts during moments when our transcribers could not understand or were not sure what was being said. We are especially grateful for updates that address these gaps.