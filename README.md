# News-predict-word-count

![ss1](https://github.com/avrland/News-predict-word-count/blob/main/chart.jpg)

Linear regression model trying to predict word count from pasted news title. Notebook has whole process from data cleaning to model training. Added form to easily paste title to try, comparison to real value. 

```
Entered title: Ze smartfonami jest jeszcze gorzej, niż myśleliśmy
Entered titles has: 50 characters
Model predicted: 7 words
Real count: 7 words
Error rate: 0.0%
```

Feel free to try it in [Google Colab](https://colab.research.google.com/github/avrland/News-predict-word-count/blob/main/WordCountPredict.ipynb).

## Flow

Input model data: character count including spaces from entered news title

Output model data: word count 

1. Enter tested news title.
2. Get character count from entered title.
3. Try to predict word count using learned model.
4. Compare prediction to real values.

