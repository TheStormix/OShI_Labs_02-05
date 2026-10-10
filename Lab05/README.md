# Основи штучного інтелекту — лабораторна робота №5

## Завдання

1. Класифікувати бінарні зображення цифр 0 і 1 розміром 4×4 за допомогою `MLPClassifier`; оптимізувати гіперпараметри за допомогою перехресної перевірки.
2. Дослідити CNN на прикладі MNIST, оцінити якість розпізнавання зображень.

## Матеріали

- `OShI_Lab05_MLP.ipynb` — локальний Jupyter Notebook для завдання 1 (NumPy, Pandas, Matplotlib, scikit-learn).
- `OShI_Lab05_CNN_Colab.ipynb` — Jupyter Notebook для виконання завдання 2 у Google Colab (Keras/TensorFlow).
- `results/` — папка із графіками та CSV, яку створюють Notebook під час виконання.

Використані в задачах набори даних різні: 4×4, класи 0/1 (завдання 1) та 28×28, класи 0–9 (MNIST, завдання 2). Тому абсолютні значення їхньої точності безпосередньо не порівнюють.

## Першоджерела

- Бінарні цифри 4×4: https://github.com/vkopey/sklearn_examples/blob/main/my_number_classify.py
- Приклад CNN з Keras: https://keras.io/getting_started/intro_to_keras_for_engineers/
- Вдосконалений Colab-варіант з LMS: https://colab.research.google.com/drive/1kC6dFq8THOP4UsbsoNoXwfWMVGbRpz3p
