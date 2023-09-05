# Audio Signal Processing - Classification by BPM

## Overview

This repository contains the resources and code related to a study conducted in 2019 focused on audio signal processing. The primary objective of this project was to classify audio files into different music genres based on calculating their beats per minute (BPM). The program developed for this purpose, named "Audio_Classify-Automation-V2.1," is a self-entrepreneurial project that demonstrates the application of audio signal processing techniques.

## About the Project

### Program Description

"Audio_Classify-Automation-V2.1" is a program designed to recognize the number of beats per minute (BPM) in audio files. It leverages the principles of audio signal processing to analyze and classify audio files into specific music genres based on their BPM. This project represents a significant undertaking in the subject of audio signal processing and serves as a testament to the application of technology in the world of music and audio analysis.

### Project Context

This study was conducted as part of a self-entrepreneurial project, showcasing the intersection of technology and music. The program's ability to classify audio files by BPM offers valuable insights into music genre categorization, which can have applications in music recommendation systems, playlist construction, and more.

## Method

The study employs a comprehensive method for classifying audio files based on their Beats Per Minute (BPM). This method involves several key steps:
- **Fast Fourier Transform (FFT)**: The algorithm begins by calculating the Fast Fourier Transform (FFT) of the audio samples. This mathematical transformation extracts frequency information from the audio, providing a fundamental basis for subsequent analysis.
- **Convolution Analysis**: Following the FFT, a convolution kernel is applied. This kernel is shifted in time across a range corresponding to common music BPM values. This process is performed individually for each frequency group obtained from the FFT output. The convolution analysis helps identify significant rhythmic patterns within the audio.
- **Machine Learning (ML)**: In the final phase of the analysis, the weights for each of the identified frequencies are thoroughly examined and assigned. This weight analysis is a pivotal step in the process, as it enables precise classification of the audio into its corresponding BPM category. The machine learning component of this method ensures a high level of accuracy in BPM classification.

This comprehensive approach combines mathematical transformations, signal analysis techniques, and machine learning to accurately categorize audio files based on their BPM, making it a robust and effective method for music genre classification.
