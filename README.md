<h1 align="center">🎧 Audio Feature Extraction Playground</h1>

<p align="center">
  Hands-on notebooks for exploring audio signals, waveform visualization, and spectral features.
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white">
  <img alt="Librosa" src="https://img.shields.io/badge/Audio-Librosa-1f2937">
</p>

## ✨ What's in this repository

This repository currently contains experimental Jupyter notebooks under `/experiments`:

- **`playground.ipynb`** — basic signal generation (sine waves), playback, and quick plotting.
- **`goblins.ipynb`** — loading real audio, waveform visualization, STFT, and mel spectrogram exploration.

## 🧰 Main libraries used

- `numpy`
- `matplotlib`
- `librosa`
- `IPython.display`
- `scipy`
- `pandas`
- `soundfile`

## 🚀 Getting started

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install the required packages:

```bash
pip install numpy matplotlib librosa scipy pandas soundfile notebook
```

4. Launch Jupyter:

```bash
jupyter notebook
```

5. Open the notebooks in `/experiments` and run cells top-to-bottom.

## 📁 Structure

```text
audio-feature-extraction/
├── experiments/
│   ├── playground.ipynb
│   └── goblins.ipynb
└── .gitignore
```

## 📝 Notes

- This is an experimentation-focused repository.
- Notebook outputs may vary depending on your local audio backend and installed package versions.
