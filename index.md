## Welcome to Bible TTS
[Paper]() - [Github](https://github.com/masakhane-io/bibleTTS)

BibleTTS is the largest, highest-quality open Text-to-Speech dataset for any language, and immediately unlocks the development of high-quality Text-to-Speech models for ten languages spoken in Sub-Saharan Africa. With up to 80 hours of single speaker, studio quality 48kHz recordings per language, we release this data under a commercial-friendly Creative Commons license.



### Corpus Statistics

The BibleTTS corpus consists of high-quality audio released as 48kHz, 24-bit, mono-channel FLAC files. Recordings for each language consist of a single speaker recorded under  professional quality, close-microphone conditions (i.e., without background noise or echo). BibleTTS is rare among public speech corpora for the volume of data available per  speaker and its suitability for creating TTS models. Furthermore, the corpus consists of ten languages which are under-represented in today’s voice technology landscape, both in academia and in industry.

|              | Unaligned <br>Hours | Unaligned<br> Samples | Aligned<br> Hours | Aligned<br> Samples |
|------|-------|------|------|------|
| Ewe         | 100.1         | 1,167         | 86.8        | 24,957      |
| Hausa        | 103.2         | 1,189         | 86.6        | 40,603      |
| Kikuyu       | 90.6          | 1,189         | --          | --          |
| Lingala      | 151.7         | 1,189         | 71.6        | 15,117      |
| Luganda      | 110.4         | 1,189         | --          | --          |
| Luo          | 80.4          | 1,189         | --          | --          |
| Chichewa     | 115.9         | 1,162         | --          | --          |
| Akuapem Twi  | 75.7          | 1,189         | 67.1        | 28,238      |
| Asante Twi   | 82.6          | 1,189         | 74.9        | 29,021      |
| Yoruba      | 93.6          | 1,189         | 33.3        | 10,228      |

### Model links and samples

|              | Model checkpoint | Configuration file | In-domain sample | Out-of-domain sample | 
|------|-------|------|------|------|
| Ewe         | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/ewe/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/asante-twi/config.json) |        |      | 
| Hausa       | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/hausa/checkpoint_1100000.pth.tar) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/hausa/config.json) |    |    |
| Kikuyu      | -- | -- | --          | --          |
| Lingala     | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/lingala/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/lingala/config.json) |      |       |
| Luganda     | -- | -- | --          | --          |
| Luo         | -- | -- | --          | --          |
| Chichewa    | -- | -- | --          | --          |
| Akuapem Twi | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/akuapem-twi/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/akuapem-twi/config.json) |      |  |
| Asante Twi  | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/asante-twi/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/asante-twi/config.json) |    |   |
| Yoruba      | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/yoruba/checkpoint_1100000.pth) | [link](https://coqui-ai-public-models.s3.amazonaws.com/OpenBible/yoruba/config.json) |    |  |
