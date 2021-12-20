# Real-Time Voice Cloning

This is an actively-developed fork of @CorentinJ's famous Real Time Voice Cloning (RTVC) repository. If you are not a developer, please download a [release](https://github.com/raccoonML/Real-Time-Voice-Cloning/releases) for the best experience.

## Development roadmap
* [ ] Integrate hifi-gan vocoder - [in progress!](https://github.com/raccoonML/Real-Time-Voice-Cloning/tree/hifi-gan)
* [ ] Add support for other languages
* [ ] Preprocess cleanup and improvements
* [ ] Encoder model updates
* [ ] Synthesizer upgrade to Tacotron2

## Windows setup
1. Install Python 3.7+ if you don't have it already. GUIDE: [Installing Python on Windows](https://www.patreon.com/posts/guide-install-in-59934677).
2. Download [**RTVC_Windows.zip**](https://github.com/raccoonML/Real-Time-Voice-Cloning/releases/download/RTVC-7/RTVC_Windows.zip) from the [RTVC-7 release](https://github.com/raccoonML/Real-Time-Voice-Cloning/releases/tag/RTVC-7).
3. Extract the zip file.
4. Create and activate a Python virtual environment. GUIDE: [Python virtual environments in Windows](https://www.patreon.com/posts/guide-python-in-59936054)
```
cd C:\path\to\RTVC\files
python -m venv venv
venv\Scripts\activate.bat
```
5. Install dependencies
```
pip install --upgrade pip
pip install torch -f https://download.pytorch.org/whl/torch_stable.html
pip install -r requirements.txt
pip install webrtcvad-wheels
```
6. Run the toolbox
```
python demo_toolbox.py
```

## Audio samples
@bluefish experiments RTVC-7<br>
https://raccoonml.github.io/bluefish_experiments/RTVC-7.html

## Credits
https://github.com/CorentinJ/Real-Time-Voice-Cloning/
