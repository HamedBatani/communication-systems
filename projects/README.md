# Digital Communication and Signal Processing in Python

I developed this project for Communication Systems at Sharif University of Technology in Fall 2025. I implemented a simulated digital communication chain and extended the work to speech quantization and correlation-based synchronization.

## Digital communication link

In [digital-link.ipynb](digital-link.ipynb), I calculate source entropy, implement Huffman encoding and decoding, and use Hamming (7,4) coding with single-bit error-correction examples. I model channel filtering, attenuation, and additive white Gaussian noise, and examine matched-filter detection. I implement 4-FSK, QPSK, and 16-QAM experiments, compare bit-error behavior across noise settings, and visualize received signals and raised-cosine pulse-shaping eye diagrams.

## Speech quantization and synchronization

In [speech-and-synchronization.ipynb](speech-and-synchronization.ipynb), I investigate speech sampling, uniform PCM quantization, and mu-law companding, comparing reconstruction errors and signal-to-noise ratios. I also examine Zadoff–Chu sequence correlations and simulate correlation-based detection of a known bit pattern and sequence identification in noise. These are educational synchronization experiments rather than a complete cellular protocol implementation.

## Files

| File | Purpose |
| --- | --- |
| [Project report](report.pdf) | My written analysis and submitted results |
| [Digital-link notebook](digital-link.ipynb) | Source/channel coding, modulation, channel simulation, and detection |
| [Speech and synchronization notebook](speech-and-synchronization.ipynb) | Quantization, audio comparison, and correlation experiments |
| [Project statement](project-statement.pdf) | Course-provided specification |
| [Original speech](speech_original.wav) | Reference audio |
| [Uniform quantization](speech_uniform.wav) | Reconstructed audio example |
| [Mu-law quantization](speech_mulaw.wav) | Reconstructed audio example |

## Reproduction

Use Python, Jupyter, NumPy, SciPy, and Matplotlib; recording/playback cells also use sounddevice. The notebooks preserve submitted outputs. Some cells depend on earlier definitions and original Windows paths; update audio paths to this directory before rerunning. I have organized the submitted work here without claiming a fresh end-to-end execution.

The implementation and report are my student work; the project statement is attributed to the course.
