# NBME - score clinical patient notes

## Competition describe
> Identify Key Phrases in Patient Notes from Medical Licensing Exams
* Timeline : 2022.02.01 - 2022.05.03
* Code Competition
* Evalutaion : micro-averaged F1, predict **a set of character spans**

**Data** 

```python
├── train
│   ├── features.csv 
│   ├── patient_notes.csv
│   └── train.csv
├── test
    ├── sample_submission.csv
    └── test.csv
```

## modeling

sth