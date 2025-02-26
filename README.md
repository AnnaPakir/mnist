# Реализация метода обратного распространения ошибки для двухслойной полностью связанной нейронной сети 
Данный проект состоит из следующих этапов:

1. Вывод математических формул для вычисления градиентов функции ошибки по параметрам нейронной сети и формул коррекции весов. Используется метод обратного распространения ошибки. [link](https://github.com/AnnaPakir/mnist/blob/main/mnist_model.ipynb)
2. Проектирование и разработка программной реализации нейронной сети, состоящей из одного скрытого слоя, на основе выведенных формул. Тестирование разработанной программной реализации. [link](https://github.com/AnnaPakir/mnist/blob/main/mnist_model.ipynb)
3. Подготовка отчета по предыдущим пунктам. [link](https://github.com/AnnaPakir/mnist/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82.pdf)
4. Разработка кода на библиотеке Keras. [link](https://github.com/AnnaPakir/mnist/blob/main/mnist_model.ipynb)
5. Разработка приложения, с использованием библиотеки gradio. Код приложения -[link](https://github.com/AnnaPakir/mnist/blob/main/app.py)

Приложение развернуто на Hugging Face [link](https://huggingface.co/spaces/AnnaPakir/mnist)

![plot](https://github.com/AnnaPakir/mnist/blob/main/mnist.gif)

Проект сделан на попульрном наборе даных - mnist.

![plot](https://github.com/AnnaPakir/mnist/blob/main/mnist.png)

В ходе проекта были выведены математические формулы для реализации нейронной сети. 

![plot](https://github.com/AnnaPakir/mnist/blob/main/form.png)

Дааные формулы были реализованы на языке Python  и протестированы с различными гиперпараметрами.

![plot](https://github.com/AnnaPakir/mnist/blob/main/loss.png)

Была создана похожая модель с помощью библиотеки Keras, протестирована на случайном примере.

![plot](https://github.com/AnnaPakir/mnist/blob/main/keras.png)

***
## Воспроизведение кода

Если есть желание вопроизвести блок с выводом формул, необходимо дополнительно установить библиотеку Latex 

```python
# Установим LaTeX
!apt-get update
!apt-get install -y texlive texlive-latex-extra texlive-fonts-recommended dvipng cm-super
```
Для повторения экспериментов в библиотеке gratio ее также необходимо установить.

```python
!pip install gradio -q
```
Перед запуском блокнота также рекомендуется сверить версии библиотек, указанных в файле requirements.txt [link](https://github.com/AnnaPakir/mnist/blob/main/requirements.txt)

Для запуска приложения на локальном пространстве достаточно скачать файл модели [link](https://github.com/AnnaPakir/mnist/blob/main/my_model.keras) и файл приложения [link](https://github.com/AnnaPakir/mnist/blob/main/app.py), а также установить вышеуказанные выше библиотеки.


