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

The ```draw``` option specified in the `config.py` file recognizes certain objects when set to `True`.  For example, if the `draw` parameter of a cat's face is set to True, the script can recognize a cat's face:

![image](https://user-images.githubusercontent.com/39937490/175439010-b480bfc0-fa4e-416c-a41c-e41eb7df38c6.png)

![cat face](https://user-images.githubusercontent.com/39937490/175438876-e516bc37-6db5-4693-90d0-6629219e633e.jpg)

Human face with smile:

![image_2022-06-24_03-44-43](https://user-images.githubusercontent.com/39937490/175439678-5b25d288-4c5e-47cc-a122-47467805b6bb.png)

Go to the script directory and run this command in terminal to run the script:

```
python run.py
```

* As soon as you run this script, it will connect your webcam and start drawing rectangles around all image faces and other objects specified in the description of this readme.
* To close the program, simply press the ```q``` button.
