# EEG Spectrogram Generator

Python program for converting BrainVision EEG recordings into word-level spectrogram datasets aligned to spoken-word onset timing.

## Included

- YAML-based configuration via `config.yaml`
- BrainVision EEG loading from `.vhdr`, `.vmrk`, `.eeg`
- 60 Hz notch filtering
- Word-aligned EEG extraction
- `256 x 256` spectrogram generation
- Multiple latency conditions such as `0`, `100`, `300` ms
- Raw, log, normalized, and log-normalized output variants

## Not Included In Git

The following folders are intentionally excluded from version control:

- `Data/`
- `outputs/`

## Run

```bash
python src/generate_eeg_spectrograms.py
```

Settings are controlled in `config.yaml`.
