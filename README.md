# dev_GoogleCollab
Google Collab Development and Notes

#### Examples [https://colab.research.google.com](https://colab.research.google.com) <br/>
- install driver
  ```
  !apt install ffmpeg
  ```
- install <software>
  ```
  !pip install <software> --ignore-installed
  ```
  
- upload Audio in Collab Notebook <br/>
  ```
  from IPython.display import Audio
  from google.colab import files
  uploaded = files.upload()
  ```
- Set upload
  ```
  fil = list(uploaded.keys())[0]
  Audio(fil)
  print(type(fil))
  ```
- Process file
  ```
  import os
  os.rename(fil,"main.mp3")
  !<software> separate -o output/ main.mp3
  ```
