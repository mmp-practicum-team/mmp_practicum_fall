# Занятие 04. OpenCV и обработка изображений

Занятие провел: Оганов Александр (tg: @welmud)

Материалы составили: Денисов Егор (denisov.official72@gmail.com), Оганов Александр (tg: @welmud)

### Источники:

- [Сергей Михайлович Прокудин-Горский](https://ru.wikipedia.org/w/index.php?title=%D0%9F%D1%80%D0%BE%D0%BA%D1%83%D0%B4%D0%B8%D0%BD-%D0%93%D0%BE%D1%80%D1%81%D0%BA%D0%B8%D0%B9,_%D0%A1%D0%B5%D1%80%D0%B3%D0%B5%D0%B9_%D0%9C%D0%B8%D1%85%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D0%B8%D1%87)
- [HSL/HSV](https://en.wikipedia.org/wiki/HSL_and_HSV)
- [Блог-пост OpenCV про цветовые пространства](https://opencv.org/color-spaces-in-opencv/)
- [Сайт демонстрации работы фильтров](https://setosa.io/ev/image-kernels/)
- [Фильтрация изображений с помощью фильтров](https://www.giassa.net/?page_id=635)
- [Фильтр Собеля](https://ru.wikipedia.org/wiki/%D0%9E%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80_%D0%A1%D0%BE%D0%B1%D0%B5%D0%BB%D1%8F)
- [Сайт с демонстрацией SVD для изображений](https://timbaumann.info/svd-image-compression-demo/)
- [Преобразование Фурье из документации OpenCV](https://docs.opencv.org/4.13.0/de/dbc/tutorial_py_fourier_transform.html)
- [CIFAR10](https://cave.cs.toronto.edu/kriz/cifar.html)
- [Torralba, Isola, & Freeman, Foundations of Computer Vision](https://visionbook.mit.edu/)
- [Пирамиды изображений из документации OpenCV](https://docs.opencv.org/4.13.0/dc/dff/tutorial_py_pyramids.html)
- [Jebamalar Leavline & Sutha, 2014](https://www.researchgate.net/publication/275038450_Design_of_FIR_Filters_for_Fast_Multiscale_Directional_Filter_Banks)
- [Keyu Tian et al., 2024](https://arxiv.org/pdf/2404.02905), примерно 1200 цитирований
- [Jia-Bin Huang, Видео с примерами смещивания изображений](https://youtu.be/U7qa7i0K9C4?si=Bea2-WRYfhTSVuuZ)
- [Морфологические операции](https://scikit-image.org/docs/0.20.x/auto_examples/segmentation/plot_morphsnakes.html)
- Ноутбук в основном основан на [ноутбуке 2023 года](https://github.com/mmp-practicum-team/mmp_practicum_fall_2023/blob/master/Seminars/04-image-processing-and-KNN/Seminar_4_cv_msu.ipynb)
- Часть материалов взята из [ноутбука 2022 года](https://github.com/mmp-practicum-team/mmp_practicum_fall_2022/blob/main/Seminars/04-image-processing-and-KNN/ImagesPython.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mmp-practicum-team/mmp_practicum_fall/blob/2026/Seminars/04-cv-knn/04-cv-knn.ipynb)