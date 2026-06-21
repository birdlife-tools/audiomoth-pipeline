# AudioMoth Data Pipeline

Python pipeline for processing AudioMoth recordings through BirdNET classifier.

## Problem

Biologists deploy autonomous audio recorders (AudioMoth) in forests that record sounds for weeks. Result: hundreds of gigabytes of audio that must be manually reviewed through spectrograms.

## Solution

Python pipeline that automatically processes audio files, cleans background noise (wind, rain), and runs them through local open-source classifiers (like BirdNET) to generate species activity matrices.

## Technical Stack

- `librosa` or `scipy` for spectral processing and noise filtering
- Batch integration with BirdNET architecture
- Generation of 24h activity graphs

## Status

🚧 Planning

## Community

Join the discussion:

[![Matrix](https://img.shields.io/badge/Matrix-Chat-black?logo=matrix](https://matrix.to/#/#audiomoth-pipeline:matrix.org)

## License

MIT — see [LICENSE](LICENSE)
