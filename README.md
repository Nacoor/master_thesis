These are the notebooks used for developing Russian-Tuvan neural machine translator.

Most of them were created based on the reference notebook https://colab.research.google.com/drive/1bayEaw2fz_9Mhg9jFFZhrmDlQlBj1YZf?usp=sharing#scrollTo=nAEe9lYNu6kv. Created by https://daviddale.ru/

The parallel corpora was taken from https://github.com/Agisight/TyvaData

nllb_600_tyv_v2.ipynb - fine-tuning of nllb200-distilled-600M on the parallel corpora;

mbart-v2.ipynb - fine-tuning of mbart50 on the parallel corpora;

train_from_zero_ru_tyv.ipynb - developing Russian-Tuvan NMT model from zero;

train_from_zero_tyv_ru.ipynb - developing Tuvan-Russian NMT model from zero;

tyvan_1_3.ipynb - fine-tuning of nllb200-distilled-1.3B on the parallel corpora;

tyvan_kz_1_3.ipynb - fine-tuning of Tilmash (https://huggingface.co/issai/tilmash) on the parallel corpora;

tyvan_600_back_translation.ipynb - fine-tuning of nllb200-distilled-600M with augmented corpora using back-translation;

tyvan_600_paraphrase.ipynb - fine-tuning of nllb200-distilled-600M with augmented corpora using round-trip translation.
