# Speech Understanding - Programming Assignment 1

This repository contains the code, reports, and presentation for Programming Assignment 1 of the Speech Understanding course.

## Question 1: Speech Processing Task Analysis 

This question involved a group analysis of a specific speech processing task.  The chosen task was [**Phoneme Recognition**].

### Contents

*   `Resources/`: Contains research papers related to the chosen task:
    *   `hubert research paper.pdf`
    *   `wave2vec research paper.pdf`
    *   `waveLM research paper.pdf`
*   `Presentation.pptx`: Presentation slides summarizing the research and analysis.
*   `Report.pdf`: Detailed report covering the following aspects:
    *   Task explanation and real-world importance.
    *   Strengths and limitations of state-of-the-art models/tools.
    *   Discussion of evaluation metrics and their limitations.
    *   Open problems and opportunities.
  

## Question 2: Spectrograms and Windowing Techniques 

This question focused on experimenting with spectrograms and windowing techniques using the UrbanSound8k dataset.

### Task A: Windowing Techniques and Spectrogram Generation

*   `Task A/code.py`: Python script implementing Hann, Hamming, and Rectangular windowing techniques, generating spectrograms using STFT, and training a classifier.
*   `Report.pdf`: Report containing:
    *   Visual comparison and analysis of spectrograms generated using different windowing techniques.
    *   Discussion of the correctness of the windowing performed.
    *   Comparison and analysis of classifier performance using features extracted from spectrograms generated with different windowing techniques.

### Task B: Spectrogram Analysis of Different Genres

*   `Task B/code.py`: Python script (if any) used for analysis.
*   `Task B/songs/`: Contains the 4 songs used for the comparative analysis (or links to the songs if they are too large for the repository).
    *   `Fitoor.wav`
    *   `O Haseena Zulfonwale.wav`
    *   `Saadda Haq.wav`
    *   `Tere Naina.wav`
*   `Report.pdf`: Report containing:
    *   Detailed comparative analysis of the spectrograms of the 4 songs from different genres.
    *   Observations and insights based on speech understanding.


## Instructions for Running the Code

### Question 2 - Task A

1.  Navigate to the `Question 2/Task A` directory.

2.  Ensure you have the following required libraries installed. You can install them using pip:

    ```bash
    pip install torch torchaudio numpy matplotlib scikit-learn pandas
    ```
    It's generally good practice to create a `requirements.txt` file in your `Task A` directory listing these dependencies.  This makes it even easier for others to replicate your environment:

    ```
    torch
    torchaudio
    numpy
    matplotlib
    scikit-learn
    pandas
    ```

    Then, users can install the dependencies with:

    ```bash
    pip install -r requirements.txt
    ```

3.  Download the UrbanSound8k dataset from the provided link and place it in a suitable location.  **[Dataset](https://goo.gl/8hY5ER)** 

4.  Run the Python script:

    ```bash
    python code.py
    ```


### Question 2 - Task B

1.  Navigate to the `Question 2/Task B` directory.

2.  Ensure you have the following required libraries installed. You can install them using pip:

    ```bash
    pip install torchaudio matplotlib torch
    ```

    As with Task A, a `requirements.txt` file in your `Task B` directory is a good practice.

3.  Place the 4 `.wav` files (Fitoor.wav, O Haseena Zulfonwale.wav, Saadda Haq.wav, and Tere Naina.wav) in the `songs/` subdirectory within the `Task B` directory.

4.  Run the Python script (if applicable):

    ```bash
    python code.py
    ```

## Google Colab Notebook

You can access and run the code for this project in this Google Colab notebooks:

### Question 2 Task A

[![Open In Colab](TASK A](https://colab.research.google.com/drive/1NQ3Y6VbQ55LWD4B77NoQoq-08zMt6duE?usp=sharing)]

### Question 2 Task B

[![Open In Colab](TASK B](https://colab.research.google.com/drive/1NAYnHSKeI4cEJfO-GeWuHbWR-7DAfr8c?usp=sharing)]

