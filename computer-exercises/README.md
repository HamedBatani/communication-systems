# Computer Exercises

I used Python notebooks to investigate communication-system concepts through numerical calculations, plots, and audio experiments.

| Exercise | My submission | Course-provided starting material | Focus |
| --- | --- | --- | --- |
| 1 | [Notebook](exercise-01-solution.ipynb) | [Template](exercise-01-template.ipynb) | Transient signals, spectral analysis, frequency-selective channels, and group delay |
| 2 | [Notebook](exercise-02-solution.ipynb) | [Original source package](exercise-02-source-package.rar) | AM, envelope and coherent detection, upper/lower SSB, and FM demodulation |
| 3 | [Notebook](exercise-03-solution.ipynb) | [Template](exercise-03-template.ipynb) | Sampling, sinc interpolation, reconstruction error, and quantization |

## Supporting files

Exercise 2 includes the supplied circuit figure `fig1.png` and my speech examples: [original](speech_original.wav), [coherent detection](speech_coherent.wav), and [envelope detection](speech_env.wav). The extracted notebook uses the same-folder audio paths. The original RAR starting package is preserved as supplied.

## Running the notebooks

Use Python with Jupyter, NumPy, SciPy, and Matplotlib. Audio-recording or playback cells may additionally require sounddevice and an audio device. Run each notebook in order and review local file paths before executing audio cells. Saved outputs document the submitted experiments; this archive is not a newly validated software release.
