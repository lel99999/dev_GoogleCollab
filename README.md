# dev_GoogleCollab
Google Collab Development and Notes

#### Examples [https://colab.research.google.com](https://colab.research.google.com) <br/>
- install driver
  ```
  !apt install ffmpeg
  ```
- install software
  ```
  !pip install <software> --ignore-installed
  ```
  
- upload Audio in Collab Notebook <br/>
  ```
  from IPython.display import Audio
  from google.colab import files
  uploaded = files.upload()
  ```
