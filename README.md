# ParkinsonDetection
"Detecting Parkinson’s Disease from speech using machine learning on the PC-GITA dataset."

## Folder Structure

- `PCGITA_RESULTS/`: Processed metadata, extracted features, plots

## Requirements

Install the following packages: 
pip install librosa soundfile praat-parselmouth pandas scikit-learn joblib tqdm

## How to Run

1. Download the PC-GITA dataset from [source].
2. Update `ROOT` path in each notebook to point to your data.
3. Run notebooks in order:
         DataPre&Extraction
         Create_spectogram
         Split_dataset
         Baseline_Classifiers
         cnn_training
         LSTM_MFCC
5. Review plots and evaluation metrics.

## License

MIT License – use for academic and research purposes.
