## Welcome to Bible TTS
[Paper](https://arxiv.org/pdf/2207.03546.pdf) - [Data](http://www.openslr.org/129/) - [Github](https://github.com/masakhane-io/bibleTTS)

BibleTTS is a large high-quality open Text-to-Speech dataset with up to 80 hours of single speaker, studio quality 48kHz recordings for each language.
We release aligned speech and text for six languages spoken in Sub-Saharan Africa, with unaligned data available for four additional languages, derived from the [Biblica open.bible](https://open.bible/) project. 
The data is released under a commercial-friendly [CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/) license.


### Corpus Statistics

The BibleTTS corpus consists of high-quality audio released as 48kHz, 24-bit, mono-channel FLAC files. Recordings for each language consist of a single speaker recorded under professional quality, close-microphone conditions (i.e., without background noise or echo). BibleTTS is rare among public speech corpora for the volume of data available per speaker and the audio quality for creating TTS models. Furthermore, the corpus consists of languages which are under-represented in today’s voice technology landscape, both in academia and in industry.  

Our aligned data is publicly available on [OpenSLR](http://www.openslr.org/129/).  

|              | Unaligned Hours | Aligned Hours | Aligned Verses | Sample |
|--------------|--------------|-------------|-------------|------------|
| Ewe          | 100.1        | 86.8        | 24,957      | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/original/ewe.flac) |
| Hausa        | 103.2        | 86.6        | 40,603      | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/original/hau.flac) |
| Kikuyu       | 90.6         | --          | --          | -- |
| Lingala      | 151.7        | 71.6        | 15,117      | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/original/lin.flac) |
| Luganda      | 110.4        | --          | --          | -- |
| Luo          | 80.4         | --          | --          | -- |
| Chichewa     | 115.9        | --          | --          | -- |
| Akuapem Twi  | 75.7         | 67.1        | 28,238      | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/original/twi-aku.flac) |
| Asante Twi   | 82.6         | 74.9        | 29,021      | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/original/twi-asa.flac) |
| Yoruba       | 93.6         | 33.3        | 10,228      | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/original/yor.flac) |  
<br>

### Demo

All trained models are integrated to Coqui TTS and can be demoed at huggingface spaces:

https://huggingface.co/spaces/coqui/CoquiTTS

### TTS model links and samples

All models are end-to-end VITS speech synthesis models trained as described in the [paper](https://arxiv.org/pdf/2207.03546.pdf).  

TTS samples coming soon!  

|              | Model checkpoint | Config file | In-domain sample | Out-of-domain sample | 
|------|-------|------|------|------|
| Ewe         | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/ewe/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/asante-twi/config.json) |   [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/ewe-sent1.wav)     |  [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/out-of-domain/ewe-sent1.wav)    | 
| Hausa       | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/hausa/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/hausa/config.json) |  [1](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/hau-sent1.wav), [2](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/hau-sent2.wav), [3](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/hau-sent3.wav)  |  [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/out-of-domain/hau-sent1.wav)  |
| Kikuyu      | -- | -- | --          | --          |
| Lingala     | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/lingala/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/lingala/config.json) |   [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/lin-sent1.wav)   |   [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/out-of-domain/lin-sent1.wav)    |
| Luganda     | -- | -- | --          | --          |
| Luo         | -- | -- | --          | --          |
| Chichewa    | -- | -- | --          | --          |
| Akuapem Twi | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/akuapem-twi/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/akuapem-twi/config.json) |   [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/twi-aku-sent1.wav)   | -- |
| Asante Twi  | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/asante-twi/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/asante-twi/config.json) |  [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/twi-asa-sent1.wav)  | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/out-of-domain/twi-asa-sent1.wav)  |
| Yoruba      | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/yoruba/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/yoruba/config.json) |  [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/in-domain/yor-sent1.wav)  | [listen](https://raw.githubusercontent.com/masakhane-io/bibleTTS/gh-pages/samples/out-of-domain/yor-sent1.wav) |  
<br>

### Links to code

#### Alignment methodology

1. [Segmentation using existing verse timestamps](https://github.com/coqui-ai/open-bible-scripts) (Sec 4.1.1)
2. [Forced alignment using pre-trained acoustic models](https://github.com/alpoktem/bible2speechDB) (Sec 4.1.2)
3. [Forced alignment from scratch](https://github.com/coqui-ai/open-bible-scripts) (Sec 4.1.3)

#### Outlier detection

[Data-checker](https://github.com/coqui-ai/data-checker) code for outlier detection (Sec 4.2)

#### TTS model training

VITS TTS models were trained with [coqui-ai](https://github.com/coqui-ai/TTS) (Sec 5)
