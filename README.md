<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## RGTM-PNO Dataset

RGTM-PNO is an open audio dataset featuring a collection of vintage piano songs in the style of ragtime, a genre that flourished around the turn of the 20th century. The dataset contains 262 audio tracks recorded in uncompressed stereo WAV format, synthetically generated using a custom soundfont and MIDI files sourced from public resources online.

## Dataset

The primary objective of this dataset is to provide accessible content for machine learning applications in music and audio research. Some potential use cases for this dataset include audio classification, automatic music transcription (ADT), music information retrieval (MIR), melody analysis, AI music generation, sound design and signal processing.

**Specifications**

- 262 piano songs (approximately 13.5 hours)
- 16-bit WAV format
- Tempo: 120 BPM (live performance in absolute time)
- Variational chorus detuning (vintage piano sound)
- Paired audio and MIDI data

## Examples

See examples folder to preview MP3 demos.


## License

This dataset was compiled by WaivOps, a crowdsourced music project managed by the sound label company Patchbanks. The audio recordings were sonified from MIDI files containing historical musical compositions believed to be in the public domain and copyright free.

The RGTM-PNO dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
## Download

The audio files are provided in 16-bit WAV format and encoded at 44.1kHz.

Direct WAV Download (7.5GB) [rgtm_pno_id_0001_wav.tar.gz](https://zenodo.org/records/13335848/files/rgtm_pno_id_0001_wav.tar.gz?download=1&preview=1)

Direct MIDI Download (70 Bytes) [rgtm_pno_id_0001_mid.tar.gz](https://zenodo.org/records/13335848/files/rgtm_pno_id_0001_mid.tar.gz?download=1&preview=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13335848.svg)](https://doi.org/10.5281/zenodo.13335848)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| rgtm | Main genre (ragtime)|
| pno | Instrument (piano)|
| id | Identification number|
| _0000 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@misc{RGTM-PNO,
author = {WaivOps},
title = {WaivOps RGTM-PNO: Open Audio Resources for Machine Learning in Music},
year = {2024},
doi = {10.5281/zenodo.13335848},
url = {https://doi.org/10.5281/zenodo.13335848},
}
```
## Additional Info

For any questions or feedback, please email info@patchbanks.com.
