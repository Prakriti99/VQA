# VQA

A VQA system takes as input an image and question about the image and produces an answer as the output. This task is applicable to scenarios encountered when visually-impaired users or intelligence analysts actively elicit visual information.

After extensive research into already implemented techniques to tackle this unique problem, we experimented on simple CNN-LSTM , Uniter, Relation attention networks.

Our file structure is as follows
```
├── score
│   ├── baseline_score.py
│   ├── score.py
│   ├── uniter_score.py
│   ├── uniter_mod_score.py
├── train
│   ├── vqa.py
│   ├── uniter_modified_train.py
│   ├── uniter_train.py
│   ├── baseline.py
│   ├── pyt1_app_train.py
```
We have separated the code into train and score to experiment with the techniques. The dataset used is DAQUAR.

To run each code:

```
python <filename.py>
```

