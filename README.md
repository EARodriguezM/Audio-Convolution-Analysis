# Audio Convolution Analysis

This Python project performs audio signal processing and analysis, focusing on convolution of audio signals with impulse responses. It uses the ThinkDSP library for digital signal processing operations.

<a href="https://github.com/EARodriguezM/Audio-Convolution-Analysis/stargazers"><img src="https://img.shields.io/github/stars/EARodriguezM/Audio-Convolution-Analysis" alt="Stars Badge"/></a> 
<a href="https://github.com/EARodriguezM/Audio-Convolution-Analysis/network/members"><img src="https://img.shields.io/github/forks/EARodriguezM/Audio-Convolution-Analysis" alt="Forks Badge"/></a>
<a href="https://github.com/EARodriguezM/Audio-Convolution-Analysis/pulls"><img src="https://img.shields.io/github/issues-pr/EARodriguezM/Audio-Convolution-Analysis" alt="Pull Requests Badge"/></a>
<a href="https://github.com/EARodriguezM/Audio-Convolution-Analysis/issues"><img src="https://img.shields.io/github/issues/EARodriguezM/Audio-Convolution-Analysis" alt="Issues Badge"/></a>
<a href="https://github.com/EARodriguezM/Audio-Convolution-Analysis/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/EARodriguezM/Audio-Convolution-Analysis?color=2b9348"></a>
<a href="https://github.com/EARodriguezM/Audio-Convolution-Analysis/blob/main/LICENSE"><img src="https://img.shields.io/github/license/EARodriguezM/Audio-Convolution-Analysis?color=2b9348" alt="License Badge"/></a> 

<!-- <a href="https://github.com/EARodriguezM/Audio-Convolution-Analysis/blob/main/esREADME.md"><img src="https://img.shields.io/static/v1?label=&labelColor=505050&message=Spanish README &color=%230076D6&style=flat&logo=google-chrome&logoColor=green" alt="website"/></a> -->

## Features

- Load and analyze different audio inputs (examples: caja, guitarra, palmadas)
- Apply various impulse responses (examples: estudio de grabación, plaza che, catedral)
- Perform convolution between input audio and impulse response
- Generate and display time-domain plots, frequency spectra, and spectrograms
- Audio playback of original, impulse, and convolved signals

## Requirements

- Python 3.x
- matplotlib
- numpy
- ThinkDSP library

## Setup

1. Clone this repository
2. Install the required packages
3. The script will automatically download `thinkdsp.py` if it's not present in the working directory.

## Usage

Run the Jupyter notebook or Python script. The program will prompt you to:

1. Choose an input audio (1: caja, 2: guitarra, 3: palmadas)
2. Select an impulse response (1: estudio de grabación, 2: plaza che, 3: catedral, 4: precaution)

The script will then generate various plots and audio outputs for analysis.

## Outputs

- Time-domain plots of input signal, impulse response, and convolved output
- Frequency spectra of input, impulse response, and output
- Spectrograms of input, impulse response, and output
- Audio playback of input, impulse response, and convolved output

## Note

This project is designed to run in a Jupyter notebook environment, which allows for interactive audio playback and plot display. Some modifications may be needed to run it as a standalone Python script.
