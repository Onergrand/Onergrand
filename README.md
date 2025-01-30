# 👋 Привет! Меня зовут Кузьмин Савелий (Onergrand) 

## 🌟 О себе
Я — студент 3-го курса в УрФУ и разработчик с опытом работы в сфере *машинного обучения* и *веб-разработки*. 

Меня увлекают технологии, и я постоянно стремлюсь узнавать что-то новое. В свободное время я занимаюсь открытыми проектами и  иногда получается писать [статьи для научных журналов](https://www.scopus.com/authid/detail.uri?authorId=59379754900).

## 💻 Языки и технологии
- **Языки программирования:** Python, JavaScript, SQL
- **Фреймворки и библиотеки:** Pytorch, FastAPI, Scikit-learn, NumPy, Pandas, React, React-Native (ранее Tensorflow, Keras)
- **Инструменты:** GitHub, Jupyter Notebook, PostgreSQL

## 📚 Мои проекты
1. **Проект 1** - [Мультиклассовая сегментация спутниковых снимков](https://github.com/Onergrand/aerial_segmentation)
   - Для этого проекта я сделал свой [датасет](https://www.kaggle.com/datasets/onergrand/russian-cities-satellite-photo-segmentation), а после реализовал модель InceptionResNetV2-Unet на Tensorflow и Keras для сегментации изображений, которая довольно плохо улавливала зависимости для сегментации 
     - mIoU = ~0.4, Dice coefficient = ~0.68
   - Я остался недоволен результатом и переписал проект на Pytorch с использованием модели Large VisionTransformer из timm для сегментации изображений, после чего результаты улучшились:
     - mIoU = ~0.55, Dice coefficient = ~0.7
   - (Подробнее в репозитории)
2. **Проект 2** - [Предсказание выживания пассажиров Титаника и предсказание популярности песен из Spotify](https://github.com/Onergrand/ml_urfu)
   - Два проекта по машинному обучению выполненные в рамках курса по машинному обучению, один по анализу данных Spotify для предсказания популярности песен и сравнения разных моделей, другой по предсказанию выживания пассажиров Титаника.
     - [spotify.ipynb](https://github.com/Onergrand/ml_urfu/blob/master/spotify.ipynb) - Лучшая модель - случайный лес (MAE - 10.10, MSE - 214.78, RMSE - 14.65, R^2 - 0.57)
     - [titanic-final.ipynb](https://github.com/Onergrand/ml_urfu/blob/master/titanic-final.ipynb) - Accuracy - 0.8
3. **Проект 3** - [Приложение на андроид для визуально-аудиального сенсорного замещения](https://github.com/Onergrand/SightSense)
   - Проект выполнялся в рамках Проектного Практикума в УрФУ в течение осеннего семестра 2024/2025 по заказу ИПЭ УрО РАН. Для разработки использовался JavaScript и React-Native. 
   - В данный момент работа все еще продолжается, в планах на будущее - переписывание проекта на Kotlin для оптимизации и улучшения производительности, а также чтобы не использовать сервер для выполнения кода визуально-аудиального замещения.
   - В планах работы есть добавление еще нескольких режимов (режим с использованием нейросети)

## 📈 Статистика GitHub
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Onergrand&show_icons=true&theme=radical)

## 📫 Как со мной связаться:
- **Email:** _saveliy.kuzmin@mail.ru_
- **Telegram:** _@Onergrand_
