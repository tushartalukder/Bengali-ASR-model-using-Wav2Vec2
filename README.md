# Bengali-ASR-model-using-Wav2Vec2
An independent, automated method of decoding
and transcribing oral speech is known as automatic speech
recognition (ASR). A typical ASR system extracts feature from
audio recordings or streams and run one or more algorithms to
map the features to corresponding texts. Numerous of research
has been done in the field of speech signal processing in
recent years. When given adequate resources, both conventional
ASR and emerging end-to-end (E2E) speech recognition have
produced promising results. However, for low-resource languages
like Bengali, the current state of ASR lags behind, although
the low resource state does not reflect upon the fact that this
language is spoken by over 500 million people all over the world.
Despite its popularity, there aren’t many diverse open-source
datasets available, which makes it difficult to conduct research
on Bengali speech recognition systems. This paper is a part of the
competition named ‘BUET CSE Fest DL Sprint’. The purpose of
this paper is to improve the speech recognition performance of
the Bengali language by adopting speech recognition technology
on the E2E structure based on the transfer learning framework.
The proposed method effectively models the Bengali language
and achieves 3.819 score in ‘Levenshtein Mean Distance’ on the
test dataset of 7747 samples, when only 1000 samples of train
dataset were used to train.

This proposed model was tested on a new hidden test
dataset in the DL Sprint Competition’s final round. There were
about 4.9k samples in the hidden dataset. This model achieved
a Levenshtein Mean Distance of 7.727 on this hidden test
dataset.
 
Paper link: https://arxiv.org/pdf/2209.08119.pdf 

Dataset links:

DL sprint Dataset: https://www.kaggle.com/competitions/dlsprint/data

Train wav files: https://www.kaggle.com/datasets/ocrteamriad/train-wavs-all-dl-sprint

Validation files: https://www.kaggle.com/datasets/sanjayacharjee/dl-sprint-validation-16k

Test wav files: https://www.kaggle.com/datasets/sanjayacharjee/testwavfilesdlsprint
