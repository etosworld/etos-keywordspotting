
### etos-keywordspotting 

PyTorch reimplementation of Google's TensorFlow convolutional neural networks for keyword spotting, which accompanies the recent release of their [Speech Commands Dataset](https://research.googleblog.com/2017/08/launching-speech-commands-dataset.html). For more details, please consult our writeup:

+ Raphael Tang, Jimmy Lin. [Honk: A PyTorch Reimplementation of Convolutional Neural Networks for Keyword Spotting.](https://arxiv.org/abs/1710.06554) _arXiv:1710.06554_, October 2017.

This is useful for building on-device speech recognition capabilities for interactive intelligent agents. can be used to identify simple commands (e.g., "stop" and "go") and be adapted to detect custom "command triggers" (e.g., "Hey Siri!").


### Demo Application

Use the instructions below to run the demo application (shown in the above video) yourself!

To deploy the demo, run the following commands:
- If you do not have PyTorch, please see [the website](http://pytorch.org).
- Install Python dependencies: `pip install -r requirements.txt`
- Install GLUT (OpenGL Utility Toolkit) through your package manager (e.g. `apt-get install freeglut3-dev`)
- Start the PyTorch server: `python .`
- Run the demo: `python utils/speech_demo.py`

If you need to adjust options, like turning off CUDA, please edit `config.json`.

Additional notes for Mac OS X:
- GLUT is already installed on Mac OS X, so that step isn't needed.
- If you have issues installing pyaudio, [this](https://stackoverflow.com/questions/33513522/when-installing-pyaudio-pip-cannot-find-portaudio-h-in-usr-local-include) may be the issue.


### refer
[honk](https://github.com/castorini/honk)
