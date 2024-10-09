# iubip
```markdown
# Simple Sort Module
## Описание
Simple Sort Module — это библиотека на языке Python, предоставляющая функции для сортировки списков различными алгоритмами (пузырьковая сортировка, быстрая сортировка).

## Требования
- Python 3.6 и выше

git clone https://github.com/vvictoria567/iubip.git

from simplesort import bubble_sort, quick_sort

## Использование

Пример использования функции `bubble_sort`:

```python
from simplesort import bubble_sort

my_list = [5, 2, 9, 1, 5, 6]
sorted_list = bubble_sort(my_list)
print(sorted_list)  # Вывод: [1, 2, 5, 5, 6, 9]

## Примеры кода
### Пузырьковая сортировка

def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
    return arr
shell

#### 7. Авторы
## Авторы

- Виктория Выхрыстюк — разработчик

## Лицензия

Этот проект лицензирован под MIT License — подробнее в файле [LICENSE](LICENSE).
