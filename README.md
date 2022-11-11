# CSYE Transcripts

This public repository hosts all of the testimony transcript files that are available as part of the [Corpus of Spoken Yiddish in Europe](https://www.yiddishcorpus.org). New transcripts are being added all the time, so please check back here for the latest additions.

As a reminder, the use of all CSYE materials, including these transcripts, is governed by our Terms of Use and requirements for proper attribution in citations, available [here](https://www.yiddishcorpus.org/csye/user-guide/).

## Download the transcripts

To save the transcripts for offline use, you can either [download a ZIP](https://github.com/YiddishCorpus/CSYE-Transcripts/archive/refs/heads/main.zip) of the repository or, if you have git installed on your computer, clone it:

    git clone https://github.com/YiddishCorpus/CSYE-Transcripts.git

## Repository structure

Transcripts are available in several different formats, each in its own directory:
* `txt/`: Text files, in both the Yiddish alphabet and YIVO transliteration, where each line contains: the name of the speaker, the start time of the utterance (seconds), the end time of the utterance (seconds), and the content of the utterance (all separated by tabs)
* `eaf/`: Transcript files, in both orthographies, that can be opened in [ELAN](https://archive.mpi.nl/tla/elan), with a separate tier for each speaker
* `TextGrid/`: Transcript files, in both orthographies, that can be opened in [Praat](https://www.fon.hum.uva.nl/praat/), with a separate tier for each speaker

There are also directories containing the transcripts in subtitle format (`srt/`, `vtt/`), which we use to embed subtitles in the videos displayed on the corpus website. We do not recommend using these because they are not as informative as the other formats (they do not include speaker names).

## Submitting corrections

If you notice any typographical errors or mistranscriptions,[^1] in either orthography, we encourage you to submit corrections to our team by [opening a support ticket](https://github.com/YiddishCorpus/CSYE-Transcripts/issues/new?assignees=ibleaman&labels=correction&template=CORRECTION_REPORT.yml&title=%E2%9C%8F%EF%B8%8F+%5BCORRECTION%5D+-+%3Ctitle%3E), which we can track and resolve. Before doing so, make sure that you have [created a GitHub account](https://github.com/join) and are signed in.

[^1]: 'UNK' and <brackets> appear in transcripts during moments when our transcribers could not understand or were not sure what was being said. We are especially grateful for updates that address these gaps.