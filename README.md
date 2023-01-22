# GigaS2S: Large Scale English-to-X Speech-to-Speech Translation

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)

*GigaS2S* is a large scale English-to-X Speech-to-Speech Translation corpus. GigaS2S is derived from [GigaSpeech](https://arxiv.org/abs/2106.06909) and [GigaST](https://arxiv.org/abs/2204.03939), by synthesizing the target speech corresponding to target translation. Currently, only parallel data for English-to-Chinese is provided. The target audios are synthesized using a high-quality single speaker Text-to-Speech model. 


## Getting the data

### English-to-Chinese

The source English audios and transcripts can be obtained from [GigaSpeech](https://arxiv.org/abs/2106.06909). And the target Chinese translations can be obtained from [GigaST](https://arxiv.org/abs/2204.03939). The target Chinese audios can be downloaded from ``data/en2zh/train_url.txt`` and extracted from the compressed ``.tar.gz`` files.

The ``train.tsv`` file contains parallel ``id``, ``src_text``, ``tgt_text`` can be downloaded from [here](http://lf3-nlp-opensource.bytetos.com/obj/nlp-opensource/datasets/GigaS2S/EN2ZH/train.tsv).


## License

GigaS2S is released under the very permissive [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

