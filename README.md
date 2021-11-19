# Audio_Signals_Analyzer 📈
The audio signals analyzer is a test and measurement instrument used to objectively quantify the audio performance.
## Introduction
This project is prepared in partial fulfillment of the requirements for the Intro to Signals & Systems subject 010123106 which is a part of the computer engineering curriculum in King Mongkut’s University of Technology North Bangkok — KMUTNB — Thailand.
## Team Members
- "Vasapol Rittideah" s6301012620171@email.kmutnb.ac.th
- "Pooncharat Wongkom" s6301012620146@email.kmutnb.ac.th
- "Phiraphon Phansa-nga" s6301012620162@email.kmutnb.ac.th
- "Thanathorn Laothaweekun" s6301012610043@email.kmutnb.ac.th
# Overview
There are 2 work functions for generating an input signal: select and load .wav audio file. Then the resulting audio signal is analyzed by displaying the waveform in the time domain and including displaying the frequency spectrum of the audio signal in the frequency-domain. Users can select more than one audio signal to combine for analysis by displaying the waveform of the audio signal in the time-domain.
## How to use
The audio signals analyzer program has 3 2-axis graphs:
- The graph at the top is used to display the audio signal waveform that is imported by clicking the Add button in time-domain. The program reads data from the audio file directory, and return sampled data and a sample rate for that data.
- The graph at the middle is used to display the audio signal that is combined with more than one audio singal and display the waveform in time-domain.
- The graph at the bottom is used to display the combined audio signal in frequency domain, i.e. displaying the frequency spectrum of the combined audio signal.

If you would like to import audio signal to the audio signals analyzer program from your local folder, you can simply click the **Add** button. Then you are supposed to select a .wav audio signal in order to analyze the signal in time-domain. The program will read data from the selected audio file by the `audioread()` matlab builtin function and plot the graph in time-domain where x-axis is the period and y-axis is the amplitude of the audio signal, and the audio file will then appear in the list box. If you would like to delete any audio file in the list box, you can click the **Delete** button. Once you click the Delete button, the audio file that is selected should eliminate from the program immediately.<br><br>

# Illustration
<p><img src="https://user-images.githubusercontent.com/88476531/142589289-718b9ee2-0aa5-4f8e-b3e8-be8ec4539b81.png" width="auto" height="600"></p>

