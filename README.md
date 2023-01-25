# Demo Face Recognition


## What is Demo Face Recognition

This demo shows how to use Taipy with a custom GUI component to capture video from your webcam and do realtime face detection.

What this application demonstrates:
* How to build a complex custom UI component for Taipy.
* How to detect and recognize faces in the image in real time using OpenCV.

### Demo Type
- **Level**: Advanced
- **Topic**: Taipy-GUI, Computer Vision
- **Components/Controls**:
  - Taipy GUI: custom GUI component
- **Other**: OpenCV

## How to run


* This demo requires Python 3.9 or 3.10. Python 3.11 is currently not supported by Taipy.
* Python dependencies are defined in the provided `requirements.txt` file.
* To visualize images in Taipy, the package `python-magic` is required (as well as `python-magic-bin` on Windows). Please see the [python-magic](https://pypi.org/project/python-magic/) page for installation.

## Introduction

- Install Python dependencies using `pip install -r requirements.txt`.
- You need a recent node envorinment to build the front-end components. You may use [nvm](https://github.com/nvm-sh/nvm) to download the latest LTS version.
- Build the front-end components from the `webcam/webui` directory using `npm run build` or `npm run build:dev`.
- Run the demo from this directory using `python demo.py`.


## Directory Structure

## License
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Installation
Want to install this demo? Check out our [`INSTALLATION.md`](INSTALLATION.md) file.

## Contributing
Want to help build this demo? Check out our [`CONTRIBUTING.md`](CONTRIBUTING.md) file.

## Code of Conduct
Want to be part of the demo's community? Check out our [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) file.
