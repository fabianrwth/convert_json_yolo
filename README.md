# convert_json_yolo
_____________________________________________________________________________________________________________________________________________

### Input: Annotations in rotated COCO JSON format 
(data/mvtec_screws.json)
```
{annotations: {'area': 3440.97, 'bbox': [184.5, 876.313, 55, 62.5631, 0], 'category_id': 7, 'id': 1001, 'image_id': 1, 'is_crowd': 0}
{'area': 116609, 'bbox': [888.3, 1249.54, 955.118, 122.089, -2.436247], 'category_id': 2, 'id': 1003, 'image_id': 1, 'is_crowd': 0}, ... }
```

<img src="https://user-images.githubusercontent.com/65671192/231610120-a1f36b0a-6eab-40cf-9475-3b4416762481.png" width="50%" height="50%">

_____________________________________________________________________________________________________________________________________________

### Output: Annotations in YOLO format
```
7 0.4564 0.1281 0.0286 0.0431
3 0.6678 0.3119 0.1302 0.416
...
```

<img src="https://user-images.githubusercontent.com/65671192/231608804-1d32b47e-c522-492e-8f07-4a51e0db34a6.png" width="50%" height="50%">
