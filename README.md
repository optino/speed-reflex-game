# Speed Reflex Game
A speed reflex game using AI object detection.

## Setup

```
conda create -n speed-reflex
activate speed-reflex
pip install numpy scipy matplotlib scikit-learn jupyter
pip install opencv-contrib-python
pip install dlib
```
## Run

usage: main.py [-h] objective

positional arguments:
  objective: The game objective to play: 
  1 - Keep It In The Middle 
  2 - Keep It In The Spot

optional arguments:
  -h, --help  show this help message and exit

### Example

```
activate speed-reflex
python main.py 1
```
