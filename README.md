# Vacation API's
## Jack Harvey 

# Overview 
Analyzing weather data from an open weather source website to identify locations with specific weather trends that are input by the user.

import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import requests
import time
from scipy.stats import linregress
import openweathermapy.core as ow
from citipy import citipy


# Running the Code
The program will fist identify a list of over 600 randomly identified coordinates to ensure that a new cities are identified each time the program is run. Citipy is used to identify the city name and adds this to a list that will be used to identify a specific URL path to extract the weather data from.

![](Output/Fig1.png)

# Sources
* Weather Data: 
  * http://api.openweathermap.org/data/2.5/weather?
