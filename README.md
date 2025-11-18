# Indic-Codecs-Evaluation

This repository presents a complete technical analysis and benchmarking of modern speech codecs — EnCodec, SNAC, and XCodec2 — evaluated across English and multiple Indic languages. It includes detailed performance comparisons, language-wise insights, and an examination of how small scale Hindi language finetuning improves the EnCodec model.

## Notebooks

### Codecs_Evaluation.ipynb
Contains the full evaluation pipeline used to benchmark all codecs.  
This notebook also includes the implementations of all metrics used for the evaluation.

### Finetuning_Encodec_Model.ipynb
Contains the complete finetuning code for the EnCodec model, including the training setup, custom loss functions, preprocessing pipeline.

## Metrics Used for Evaluation

The codecs are compared using the following objective and perceptual metrics:

- SI-SDR  
- PESQ  
- STOI  
- Mel-Cepstral Distortion (MCD)  
- Mel-Spectrogram Distance  
- STFT Distance  
- SDR  
- Latency  
- Real-Time Factor (RTF)  
- Compression Ratio  

These metrics collectively assess speech quality, intelligibility, spectral distortion, reconstruction accuracy, and runtime performance.

