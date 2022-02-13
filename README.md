# <p align="center">Hand Gesture Recognition</p>
<p align="center"> 
<a href="https://www.linkedin.com/in/roy-ashish">
<img alt="linkedin" src="https://img.shields.io/badge/-Ashish Roy-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/roy-ashish"></a>
<img src="https://img.shields.io/badge/Version-1.0.0-blue" />
<img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
<img src="https://img.shields.io/badge/Python-100%25-yellow?style=flat&logo=python&logoColor=yellow" />
</p><img align='right' src="https://user-images.githubusercontent.com/78773964/153772888-5aa1589a-6680-432b-8c5e-ed8c02e249a7.jpeg" width="150">

## Motivation & Goal 

The essential aim for building this project is to learn to create a natural interaction between human and computer where the recognized gesture can be used for conveying meaningful information for people with Disability. This is just a basic step of recognizing a hand gesture or rather say count the number of fingers.

## Installation

Use the package manager pip or homebrew to install any necessary packages for your environment if you are running on local machine.

```bash
pip3 install opencv-python  #for python3

pip install opencv-python   #for python2
```

## Packages Used

```python
import cv2
import numpy as np
import math
```

## System Flow

<img width="669" alt="Screen Shot 2022-02-13 at 3 20 14 PM" src="https://user-images.githubusercontent.com/78773964/153773643-476eb560-ea1c-479e-96c3-8dc0bebb2aaf.png">

## Image Processing Flow

<img width="700" alt="Screen Shot 2022-02-13 at 3 20 49 PM" src="https://user-images.githubusercontent.com/78773964/153773735-46c399a2-8398-44ba-b5aa-d31e701215ae.png">

## Algorithm Used

### Convex Hull Algorithm (Jarvis's Algorithm or Wrapping)
Given a set of points in the plane, the convex hull of the set is the smallest convex polygon that contains all the points.
![image](https://user-images.githubusercontent.com/78773964/153774013-5672087e-c478-4880-839f-0b72521d39fe.png)

## Output

<img width="1024" alt="image" src="https://user-images.githubusercontent.com/78773964/153773905-fe9650ec-e5c0-4a68-b9c4-3c300f39751b.png">

## How to Use

Navigate the terminal to the directory where the script is located using the cd command and type the following in your terminal.
```bash
python handG.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
