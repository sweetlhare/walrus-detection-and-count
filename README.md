# walrus-detection-and-count
Решение кейса **"ИИ на страже популяции ненецких моржей"** для хакатона в Хабаровске в рамках Цифрового Прорыва: сезон ИИ.

- Результаты обработки тестовых данных находятся в архиве test_results_post_2.zip

Алгоритм построен на **Mask R-CNN** из библиотеки mmdetection.

- prepare_data_coco.ipynb - преобразование данных в формат coco (производилось локально)
- train.ipynb - обучение модели (производилось в кэггле)
- inference.ipynb - инференс на тестовых данных (производилось в гугл колабе)

Пример работы алгоритма.

![Alt Text](https://github.com/sweetlhare/walrus-detection-and-count/blob/main/morzh.gif)
