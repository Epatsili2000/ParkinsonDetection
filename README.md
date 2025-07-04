# ParkinsonDetection
"Detecting Parkinson’s Disease from speech using machine learning on the PC-GITA dataset."

## Folder Structure

- `PCGITA_RESULTS/`: Processed metadata, extracted features, plots

## Requirements

Install the following packages: 
pip install librosa soundfile praat-parselmouth pandas scikit-learn joblib tqdm

## How to Run

1. Download the PC-GITA dataset.
2. Update `ROOT` path in each notebook to point to your data.
3. Run notebooks in order:
         DataPre&Extraction.ipynb
         Create_Spectogram.ipynb
         SplitDataset.ipynb
         Baseline_classifiers.ipynb
         cnn_training.ipynb
         LSTM_MFCC.ipynb
5. Review plots and evaluation metrics.

## License

MIT License – use for academic and research purposes.
