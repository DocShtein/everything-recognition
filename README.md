## Project overwiev

The script recognizes the following object through the webcam:
* faces (front & profile), eyes and smiles of people
* people in full growth
* cat faces

## How to install

* For the script to work, you must have a webcam connected to your pc or laptop and configured.
* Python3 should be already installed. Then use pip (or pip3, if there is a conflict with Python2) to install dependencies:
```
pip install -r requirements.txt
```
## How to use

Go to the script directory and run this command in a terminal:

```python .\run.py```

* As soon as you run this script, it will connect your webcam and start drawing rectangles around all image faces and other objects specified in the description of this readme.
* To close the program, simply press the ```q``` button.
