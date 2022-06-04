# CONFIT: Toward Faithful Dialogue Summarization with Linguistically-Informed Contrastive Fine-tuning

We propose a training strategy that improves the factual consistency and overall quality of summaries via a novel contrastive fine-tuning, called ConFiT. Based on our linguistically-informed typology of errors, we design different modular objectives that each target a specific type.

The code is based on huggaface's [transformers](https://github.com/huggingface/transformers). Thanks to them! 

## Pretrained models

Download the T5, Pegasus, and BART models from [Google Drive]().

## Test

## Annotation

[Google Drive](https://drive.google.com/drive/folders/1-IkrMDvDoBaEq9Y_ghSyxaAQIQRNCUbu?usp=sharing) is the unblinded annotation files that I used to compute the distributions in Tables 3 and 4. 

And see analysis.ipynb: the script to calculate the score.

## Citation
```
@article{tang2021confit,
  title={CONFIT: Toward Faithful Dialogue Summarization with Linguistically-Informed Contrastive Fine-tuning},
  author={Tang, Xiangru and Nair, Arjun and Wang, Borui and Wang, Bingyao and Desai, Jai and Wade, Aaron and Li, Haoran and Celikyilmaz, Asli and Mehdad, Yashar and Radev, Dragomir},
  journal={arXiv preprint arXiv:2112.08713},
  year={2021}
}

```
