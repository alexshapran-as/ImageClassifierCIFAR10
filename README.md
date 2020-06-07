# ОИРС. Домашнее задание №3. Классификация изображений
Нейросеть ршает задачу классификации изображений по следующим категориям: 
* самолеты
* автомобили
* грузовики
* корабли
* птицы
* кошки
* олени
* собаки
* лягушки
* лошади

Для обучения нейронной сети использовался датасет CIFAR-10 — 60 тысяч изображений.
Размер изображений — 32 × 32 пикселя.
Поддержка этого датасета включена в Keras.
Для повышения качества обучения сети из каждого изображения в датасете создаются дополнительные изображения 
со случайными сдвигами, поворотами и отражениями по горизонтали.

**Пример работы обученной сети:**

![input image](example.png "Пример работы обученной сети")