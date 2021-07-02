## Branch Notice

Basic On [ultralytics/yolov3](https://github.com/ultralytics/yolov3) repository


## Requirements

Python 3.8 or later with all requirements.txt dependencies installed, including `torch>=1.7`. To install run:
```bash
$ pip install -r requirements.txt
```


## Training

```python
python train.py --data xxx.yaml -cfg yolov3.yaml --weights '' --batch-size 24
```