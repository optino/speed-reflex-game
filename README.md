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
  gameId: The game to play: 
  1 - Centre Challenge
  2 - Spot Challenge

optional arguments:
  -h, --help  show this help message and exit

### Example

```
activate speed-reflex
python main.py 1
```

## Credits

1. [GameAudio - Win Spacey][1]
2. [Tuudurt - Level win][2]

[1]: https://freesound.org/people/GameAudio/sounds/220184/
[2]: https://freesound.org/people/Tuudurt/sounds/258142/
