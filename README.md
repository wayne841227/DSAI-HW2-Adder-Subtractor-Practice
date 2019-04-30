# DSAI-HW2 Adder & Subtractor Practice

## training parameter (use Addition model experience)
### no modified parameter
TRAINING_SIZE = 80000
DIGITS = 3
iteration : 100
accuracy: 0.9925

### modified TRAINING_SIZE to 8000
TRAINING_SIZE = 8000
DIGITS = 3
iteration : 100
accuracy: 0.22

### modified iteration to 10
TRAINING_SIZE = 8000
DIGITS = 3
iteration : 10
accuracy: 0.37525

## Can we apply the same training approach for multiplication?

3位數乘法最多會有6位數答案，train_y size 需改為6，輸出位數變多，需要更大的training size才能保持accuracy

有做multiplication的實驗，accuracy: 0.1781，非常低，有可能需要更大的training size


