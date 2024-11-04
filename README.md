# transformer_ngrams

This repository contains data associated to the paper "Understanding Transformers via N-Gram Statistics" (https://www.arxiv.org/abs/2407.12034). In that work, we aggregrated various n-gram statistics to form n-gram rules whose predictions could be compared with those made by a language model. We release such rules data so that others can repeat our experiments for measuring rule-like behavior. The only thing required of the user is to provide the set of model predictions (by running their own inference on the sequence of tokens we provide). Models should be trained on the dataset provided since the nature of the dataset processing and tokenization affects the n-gram statistics.

## Installation

See colab for how to interpret and use the data.

## Citing this work

Add citation details here, usually a pastable BibTeX snippet:

```latex
@misc{nguyen2024understandingtransformersngramstatistics,
      title={Understanding Transformers via N-gram Statistics},
      author={Timothy Nguyen},
      year={2024},
      eprint={2407.12034},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2407.12034},
}
```

## License and disclaimer

Copyright 2024 DeepMind Technologies Limited

All software is licensed under the Apache License, Version 2.0 (Apache 2.0);
you may not use this file except in compliance with the Apache 2.0 license.
You may obtain a copy of the Apache 2.0 license at:
https://www.apache.org/licenses/LICENSE-2.0

All other materials are licensed under the Creative Commons Attribution 4.0
International License (CC-BY). You may obtain a copy of the CC-BY license at:
https://creativecommons.org/licenses/by/4.0/legalcode

Unless required by applicable law or agreed to in writing, all software and
materials distributed here under the Apache 2.0 or CC-BY licenses are
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the licenses for the specific language governing
permissions and limitations under those licenses.

This is not an official Google product.
