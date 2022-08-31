# Yolov7-Close-People-Counter (DEMO VERSİON)
Counting Close People with Yolov7


- Censoring and counting all cigarettes on the screen and saving smoker's faces in the folder or any database
- Useful for public non-smoking areas
- Code can run on Both (CPU & GPU)
- Video/WebCam/External Camera/IP Stream Supported

# How to run Code:
- clone the repository:
- `!git clone https://github.com/DoganK01/Yolov7-Close-People-Counter.git`
- `cd /content/Yolov7-Close-People-Counter`

# Upgrade pip with the mentioned command below.
- `pip install --upgrade pip`

# Install requirements
- `!pip install -r requirements.txt`

# Weights get
- `%%bash`
- `wget -P /content/Yolov7-Close-People-Counter/weights https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7x.pt`

# Upgrade pyyaml
- `!pip install --upgrade pyyaml==5.3.1`

# Using Counter Example:
- `!python detect.py --weights /content/Yolov7-Close-People-Counter/weights/yolov7x.pt --source /content/Yolov7-Close-People-Counter/inference/images/bus.jpg --distance_rate 170 --no-trace`

# Results
![bus](https://user-images.githubusercontent.com/98788987/187530696-fd35e673-9ab3-424b-91bb-39008bbef001.jpg)

# Sample Video
https://www.youtube.com/watch?v=myC3QUAiJFw&ab_channel=do%C4%9Fankeskin
