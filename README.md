## 💻 Языки и технологии
- **Языки программирования:** Python, SQL
- **Фреймворки и библиотеки:** Pytorch, Scikit-learn, NumPy, Pandas, OpenCV, seaborn
- **Инструменты:** Git, Jupyter Notebook, SQLite, PostgreSQL

## 📚 Мои проекты
1. **Проект 1** - [Мультиклассовая сегментация спутниковых снимков](https://github.com/Onergrand/aerial_segmentation)
   - Для этого проекта я сделал свой [датасет](https://www.kaggle.com/datasets/onergrand/russian-cities-satellite-photo-segmentation), а после реализовал модель InceptionResNetV2-Unet на Tensorflow и Keras для сегментации изображений, которая довольно плохо улавливала зависимости для сегментации 
     - mIoU = ~0.4, Dice coefficient = ~0.68
   - Я остался недоволен результатом и переписал проект на Pytorch с использованием модели Large VisionTransformer из timm для сегментации изображений, после чего результаты улучшились:
     - mIoU = ~0.54, Dice coefficient = ~0.67
   - (Подробнее в репозитории)
2. **Проект 2** - [Предсказание выживания пассажиров Титаника и предсказание популярности песен из Spotify](https://github.com/Onergrand/ml_urfu)
   - Два проекта по машинному обучению выполненные в рамках курса по машинному обучению, один по анализу данных Spotify для предсказания популярности песен и сравнения разных моделей, другой по предсказанию выживания пассажиров Титаника.
     - [spotify.ipynb](https://github.com/Onergrand/ml_urfu/blob/master/spotify.ipynb) - Лучшая модель - случайный лес (MAE - 10.10, MSE - 214.78, RMSE - 14.65, R^2 - 0.57)
     - [titanic-final.ipynb](https://github.com/Onergrand/ml_urfu/blob/master/titanic-final.ipynb) - Accuracy - 0.8


## 📫 Как со мной связаться:
- **Email:** _saveliy.kuzmin@mail.ru_
- **Telegram:** _@Onergrand_
