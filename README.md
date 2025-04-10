# Задача "Прыжки по списку"

## Описание задачи

Вам дан список чисел `nums`, где каждый элемент списка представляет собой максимальную длину прыжка с текущей позиции. Изначально вы находитесь на первом элементе списка (индекс 0). Задача — определить, можно ли добраться до последнего элемента списка, выполняя прыжки по заданным правилам.

Каждый элемент списка задает максимальную длину прыжка с этой позиции, и ваша задача — проверить, возможно ли добраться до последнего элемента, двигаясь по списку.

### Примеры ввода-вывода

**Пример 1:**

**Ввод**:
```python
example_1 = [2, 3, 1, 1, 4]
```
**Вывод:**
`True`

Пояснение: Из первого элемента nums[0] можно перепрыгнуть на второй элемент nums[1], а затем с nums[1] можно прыгнуть на последний элемент nums[4], что является концом списка.

**Пример 2:**
```python
example_2 = [3, 2, 1, 0, 4]
```
**Вывод:**
`False`

Пояснение: В этом примере, даже если вы прыгнете на второй элемент nums[1], а затем на третий элемент nums[2], вы не сможете прыгнуть дальше, так как nums[3] равен 0 и не позволяет двигаться дальше. Следовательно, добраться до последнего элемента невозможно.

## Инструкция по запуску

* **Клонировать репозиторий:** начала клонируйте репозиторий на свой локальный компьютер, используя команду:
```bash
 git clone https://github.com/ViktoriaKonoplyanik/ttest_task.git
```
* **Перейдите в каталог проекта:** Перейдите в директорию с проектом:
```bash
 cd ttest_task
```
* **Запуск программы:** Для запуска программы используйте Python:
```bash
 python solution.py
```
**Взаимодействие с пользователем:** После запуска программа предложит вам выбрать между генерацией случайного списка или вводом собственного списка. Также предусмотрены примеры заранее заданных списков.


## Контакты
Если возникли вопросы или предложения по улучшению проекта, связаться можно по адресу: [v375447086861@gmail.com](mailto:v375447086861@gmail.com).