# Audio_Signals_Analyzer 📈
The audio signals analyzer is a test and measurement instrument used to objectively quantify the audio performance.
## Introduction
This project is prepared in partial fulfillment of the requirements for the Intro to Signals & Systems subject 010123106 which is a part of the computer engineering curriculum in King Mongkut’s University of Technology North Bangkok —<a href="https://www.kmutnb.ac.th/">KMUTNB</a>— Thailand.
## Team Members
- "Vasapol Rittideah" s6301012620171@email.kmutnb.ac.th
- "Pooncharat Wongkom" s6301012620146@email.kmutnb.ac.th
- "Phiraphon Phansa-nga" s6301012620162@email.kmutnb.ac.th
- "Thanathorn Laothaweekun" s6301012610043@email.kmutnb.ac.th
# Overview
There are 2 work functions for generating an input signal: select and load .wav audio file. Then the resulting audio signal is analyzed by displaying the waveform in the time domain and including displaying the frequency spectrum of the audio signal in the frequency-domain. Users can select more than one audio signal to combine for analysis by displaying the waveform of the audio signal in the time-domain.
## How to use
The audio signals analyzer program has *3* 2-axis graphs:
- The graph at the top is used to display the audio signal waveform that is imported by clicking the Add button in time-domain. The program reads data from the audio file directory, and return sampled data and a sample rate for that data.
- The graph at the middle is used to display the audio signal that is combined with more than one audio singal and display the waveform in time-domain.
- The graph at the bottom is used to display the combined audio signal in frequency domain, i.e. displaying the frequency spectrum of the combined audio signal.

If you would like to import audio signal to the audio signals analyzer program from your local folder, you can simply click the **Add** button. Then you are supposed to select a .wav audio signal in order to analyze the signal in time-domain. The program will read data from the selected audio file by the `audioread()` matlab builtin function and plot the graph in time-domain where x-axis is the period and y-axis is the amplitude of the audio signal, and the audio file will then appear in the list box. If you would like to delete any audio file in the list box, you can click the **Delete** button. Once you click the Delete button, the audio file that is selected should eliminate from the program immediately.<br><br>
In addition, users can merge one or more audio file as implied by clicking the **Merge selected files** button. The program will merge the selected files and reads data from the merge file, and then display the waveform at the middle graph. If you would like to listen to the audio file, you can click the **Play** button to play the audio file, the **Pause/Resume** to temporary stop the audio file or play the audio file again from the point at which it was paused, and the **Stop** button to stop playing the audio file. You can increase or decrease the volume of the audio file by silding the volume silder below the **Stop** button as well.

## Addition Features
- The **Reverse** option on the audio operation panel reverses the selected audio file, so that the end of the audio will be heard first and the beginning last—which means that it essentially flips the waveform on its head. You can also create interesting sound effects by recording natural events and reversing the audio.
- The **Inverse** option inverts the phase of the selected audio file. It is mostly used to avoid the effect of phase cancellation. For example, when you record an audio file with multiple microphones, their phase will probably cancel each other. Therefore, if you visually notice that thing happens, inverting one of the channels shuold  solve the issue.
- The **Normalize** option is the audio normalization which is a process that increase the level of the selected audio file by a constant amount so that it reaches a target—or norm. Normalization applies the same level increase to the entire duration of the audio file.
- The **Speed** option is an option set to adjust the audio speed. You must type a number or click the up/down button to adjust the audio speed. Note that this option only change the audio sample rate not the audio data.
# Illustration
![Capture](https://user-images.githubusercontent.com/88476811/142654317-c32e378a-e1cc-41fb-af47-30bd7d2937b6.JPG)

# More Feature
- Reverse Audio File
- Invert
- Normalize
- Change Audio Speed (Change SampleRate Without Change audio data)
- Change Audio Gain
- Trim Audio
- Export Merge Audio to .wav file
