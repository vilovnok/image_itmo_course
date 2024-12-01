# Task 1

### Задача: многоклассовая классификация
### Датасет: CIFAR-10
### Классы:
- plane
- car
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck

### Архитектура: ResNet34

### Гиперпараметры:
- оптимайзер: AdamW
- lr: 0.001 
- betas: (0.8, 0.999)
- scheduler: ExponentialLR
- epoch: 7
- batch: 16 


### Метрики
По всем классам:
- precision = 0.75
- recall = 0.75
- f1 = 0.7497


Accuracy для каждого класса:
| Класс | Точность |
|-------|----------|
| plane | 78.2 %   |
| car   | 84.9 %   |
| bird  | 63.7 %   |
| cat   | 60.1 %   |
| deer  | 70.1 %   |
| dog   | 60.8 %   |
| frog  | 82.4 %   |
| horse | 79.8 %   |
| ship  | 80.0 %   |
| truck | 82.2 %   |

# Логирование
Графики во время обучения
### Loss train и test
![Мое изображение](images/loss_train.png)
![Мое изображение](images/loss_test.png)
### Метрики 
![Мое изображение](images/f1.png)
![Мое изображение](images/recall.png)
![Мое изображение](images/precision.png)