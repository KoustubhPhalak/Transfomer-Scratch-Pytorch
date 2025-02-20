# Transfomer-Scratch-Pytorch
Transformer from 'Attention is all you need' implemented from scratch in Pytorch.

For training, I use the Europarl German-English training corpus. By training the transformer for 10 epochs, I roughly observe around 25-30 BLEU score, which is in the expected range of the original paper (28.4 BLEU score). The corpus can be downloaded [here](https://www.statmt.org/europarl/v7/de-en.tgz). For more language pair data, one can check [this link](https://www.statmt.org/europarl/)

## Transformer parameter values
Model dimension <code>**(d_model)**</code> = 512
Number of Attention Heads **(n_heads)** = 8
Number of Encoders **(num_encoder_layers)** = 4
Number of Decoders **(num_decoder_layers)** = 4
Maximum sequence length **(max_len)** = 128
Feedforward layer hidden size **(dim_feedforward)** = 2048
Vocabulary size **(vocab_size)** = 37000 (same as original paper)
Batch size **(batch_size)** = 64
************************************
**TOTAL PARAMETER COUNT** ≈ 86M