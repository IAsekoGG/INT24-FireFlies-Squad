# INT24 FireFlies Squad
Дякуємо, що завітали до нашого репозиторію. В якості моделі ми обрали Mask_RCNN, яку адаптували під наш набір даних, дотренували та застосували рішення передобробки зображень, яке описано в коді ^^
## Інсталяція
Спочатку треба встановити необхідні версії бібліотек з requirements.txt. 
```
pip install -r requirements.txt
```
Цього буде достатньо, щоб запустити interference.ipynb та train.ipynb на вашій машині, все інше має встановитися автоматично.

Якщо не встановляться requirements, то про всяк випадок є лінк на кагл, головне там запускати в нашому оточенні:

https://www.kaggle.com/kayuchks/mask-rcnn-and-coco-final-version

https://www.kaggle.com/kayuchks/interference/edit
## Як використовувати
train.ipynb:

Треба в першій комірці вказати шляхи до набору даних та папки, в яку буде зберігатися кеш і можна 4 години насолоджуватися тренуванням.

interference.ipynb:

Треба вказати шляхи та встановити модель та конфігурацію. Це треба зробити один раз, потім цей блок можна закоментувати.

## Джерела:
https://www.github.com/matterport/Mask_RCNN

https://www.github.com/i-pan/kaggle-rsna18

https://www.kaggle.com/code/pneumonia-classification-fine-tuning-resnet-83-3

https://www.kaggle.com/code/rsna-pneumonia-detection-cnn-capstone-9
