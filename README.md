# NLI Data Sanity Check: Assessing the Effect of Data Corruption on Model Performance

This repository contains data and a sample script for the paper:

**Aarne Talman, Marianna Apidianaki, Stergios Chatzikyriakidis, Jörg Tiedemann. 2021 (forthcoming). NLI Data Sanity Check: Assessing the Effect of Data Corruption on Model Performance. Proceedings of NoDaLiDa.**

*Pre-trained neural language models give high performance on natural language inference (NLI) tasks. But whether they actually understand the meaning of the processed sequences remains unclear. We propose a new diagnostics test suite which allows to assess whether a dataset constitutes a good testbed for evaluating the  models' meaning understanding capabilities. We specifically apply controlled corruption transformations to  widely used  benchmarks (MNLI and ANLI), which  involve removing entire word classes and often lead to non-sensical sentence pairs.  If model accuracy on the corrupted data remains high, then the dataset is likely to contain statistical biases and artefacts that guide prediction. Inversely, a large decrease in model accuracy indicates that the original dataset provides a proper challenge to the models' reasoning capabilities. Hence, our proposed controls can serve as a crash test for developing high quality data for NLI tasks.*
