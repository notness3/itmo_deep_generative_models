# homework 3

В этой ветке содержится решение 3-ей домашней работы по курсу "Глубокие генеративные модели". Код решения и использованные библиотеки приведены в `Stylegan2.ipynb`

Author: Фёдорова Инесса Алексеевна

В ходе работы были реализованы пункты, приведенные ниже

## Первый пункт отчета
- Кадрированы изображения для соответствия данным из трейна, блок 
- Найдены проекции изображений в пространстве StyleGAN, методами из ноутбука (encoder - e4e_ffhq_encode.pt, лоссы Rec_Loss, Lpips_Loss, Reg_Loss)

<img src="imgs/latent_images.png" alt="example" width="800" />


## Style transfer

Результаты переноса трех стилей (использованные индексы из вектора W+ [ 8, 10, 11, 12, 13, 14, 15, 16, 17])

### Стиль 1
<img src="imgs/style_transfer1.png" alt="example" width="800" />

### Стиль 2

<img src="imgs/style_transfer2.png" alt="example" width="800" />

### Стиль 3

<img src="imgs/style_transfer3.png" alt="example" width="800" />

## Expression Transfer

Результаты переноса трех эмоций (использованные индексы из вектора psi=0.5, W+=[0, 1, 4, 5, 6, 7, 9])

### Эмоция 1
<img src="imgs/expr_transf1.png" alt="example" width="800" />

### Эмоция 2

<img src="imgs/expr_transf2.png" alt="example" width="800" />

### Эмоция 3

<img src="imgs/expr_transf3.png" alt="example" width="800" />

## Face swap

Реализован перенос лиц с использованием ArcFace Loss

<img src="imgs/swap_table.png" alt="example" width="800" />
