# Geo location Google API 4G Sites

Geo location from Google API based in given lat lng data

## Setup

### Google API KEY

* Access [Developer Console](https://console.developers.google.com) with you Gmail account

* Create a key supporting the APIs below:
  * Places API
  * Geolocation API
  * Geocoding API
  * Maps JavaScript API

Copy your key, then rename file *key_example.py* to *key.py*, put the key you get above in the *__key* variable. Save the file

```
class GoogleKey:
  def __init__(self):
    self.__key = 'PUT YOUR GOOGLE KEY API HERE'

  def getKey(self):
    return self.__key
```

### Jupyter

Install ANACONDA with Python 3.6 or better

Run in Jupyter the notebook *geoGoogle_example.ipynb*

Usually each query to Google API takes 600 ms


