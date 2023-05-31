# Submission Assumptions

- Submission assumes that the COCO 2017 validation split and its corresponding annotations file has been downloaded to the machine.

- Format of the path of the dataset and the annotation file (editable in the notebook):
```
~/val2017 # COCO 2017 validation split images

~/val2017/annotations/instances_val2017.json # COCO 2017 annotations file
```

- Make sure that the annotations file is in a folder named 'annotations' inside the same directory of where the COCO images are saved.

- Main notebook is master.ipynb.

- Create a folder named `cropped` for cropped image masks.

## Install

```
pip install -r requirements.txt
```


## Diagram

![Program Flow of Project](/images/flow.jpg)