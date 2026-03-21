# CyberMedia Project: Audio Source Separation

This repository contains the laboratory and research project for the **Introduzione ai Cybermedia** course.

## Core Technology

The project idea is to compare the actual state-of-the-art in audio source separation: Demucs and HPSS. Demucs is a deep learning-based model developed by Facebook AI Research, while HPSS (Harmonic/Percussive Source Separation) is a traditional signal processing technique that we will implement from scratch.

## Project Structure

- `Demucs.ipynb`: the main Jupyter Notebook.
- `requirements.txt`: List of Python dependencies.
- `songs/` _(ignored by git)_: put your input `.wav` mixes here.
- `output/` _(ignored by git)_: the separated stems (`vocals.wav`, `bass.wav`, etc.) will be saved here.

## How to Run the Code

To run the code, follow these steps:

1. Clone the repository:
   ```bash
   git clone
   ```
2. Navigate to the project directory
3. Create a virtual environment with python 3.10:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Install Jupyter Notebook:
   ```bash
   pip install notebook
   ```
7. Start Jupyter Notebook:
   ```bash
    jupyter lab
   ```
