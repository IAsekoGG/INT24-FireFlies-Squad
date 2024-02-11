# INT24 FireFlies Squad
Дякуємо, що завітали до нашого коду)
## Instalation
Спочатку треба встановити необхідні версії бібліотек з requirements.txt. 
```
pip install -r requirements.txt
```
Цього буде достатньо, щоб запустити interference.ipynb та train.ipynb.
## How to use
No you can start MapFinder by running start.sh:
```commandline
bash start.sh
```
Then you will have to select initialization type. By checkpoint of map that already created, all such checkpoints saved in checkpoint folder in root dir of the app, or by creation of new map, checkpoint of it could be saved then.

After that, when you load a map, you can choose one of three options:
> Find by drone image - it require image from drone, approximate position of drone and radius of error and predict sector of drone allocation. 

> Find all in circle - it require approximate position of drone and radius of error and give all sectors in area.

> Test hardware - it require power of test and give time that was required to pass it
