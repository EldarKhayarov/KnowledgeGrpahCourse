## Обучение с подкреплением в окружении Mountain_Car

## Грошев Виталий Александрович

Для выполнения работы была выбрана среда [Mountain_Car](https://gymnasium.farama.org/environments/classic_control/mountain_car/)

#### Описание среды

##### Action space

0. Ехать влево (к отрицательным координатам по Х)
1. Ничего не делать
2. Ехать вправо (к положительным координатам по Х)

##### Observation space

Вектор из двух значений.
[0] - координата машины вдоль оси X
[1] - текущая скорость машины (отрицательная - влево, положительная - вправо)


#### Обучение

Код запускался в среде google colab.
Для обучения количество шагов было устанавлено на 100 `timestamp=100`. 
  

#### Результаты
100 шагов обучения оказалось недостаточно, чтобы машина научилась доезжать до флажка,
однако этого хватило чтобы продемонстрировать движение машинки на анимации.
В ходе обучения и отрисовки анимации код выдал несколько предупреждений об использовании устаревших методов, 
но это не критично и позволяет удостоверится в работоспособности окружения. 

