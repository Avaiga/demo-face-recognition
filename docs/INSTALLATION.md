# Installation

This demo requires Python 3.9 or 3.10. Python 3.11 is currently not supported by Taipy.

**Important Note**: To visualize images in Taipy, the package `python-magic` is required (and `python-magic-bin` on Windows). Please see the [python-magic](https://pypi.org/project/python-magic/) page for installation.


To install this demo:

```
git clone git@github.com:gmarabout/taipy-demo-face-recognition.git
cd taipy-demo-face-recognition
```

To install the dependencies:
```
pipenv install
```

or, if you want to develop in the demo:
```
pipenv install --dev
```

Then you need to build the front-end JavaScript:

```
cd taipy-demo-face-recognition/webcam/webui
npm install
npm build
```


And finally, to run the demo:
```
pipenv run python main.py
```
