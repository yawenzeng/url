# Moment is Important: Language-Based Video Moment Retrieval via Adversarial Learning (URL)

# Environment Settings
We use the framework pytorch.

* pytorch version: '1.2.0'
* python version: '3.5'

## Example to run the codes
Run AVMR：
```
python main.py
```

## Dataset
We provide two processed datasets: Charades-STA && TACoS
The strategy of multi-scale sliding windows is utilized to segment each video with the size of [64, 128, 256, 512] frames with 80% overlap and we randomly selected 80% and 20% of them for training and testing, respectively.

All features are saved in ./feature_all_train, ./feature_all_test. 
* These two processed features are available for downloading here: https://drive.google.com/open?id=1-AMToMuTlPRY1C2n0ZoyKrwBsVPehbFK
* The original videos and their corresponding caption annotations/querys: https://github.com/jiyanggao/TALL and http://www.coli.uni-saarland.de/projects/smile/tacos

## Workspace
/workplaceTest and /workplaceTrain that processes videos in advance as a runtime workspace.

#
