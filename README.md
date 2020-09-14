# Примеры работы с сервисом AI Cloud от SberCloud

В репозитории приведены примеры использования сервиса AI Cloud для решения ML задач.

## Model Training (обучение моделей)

Базовые примеры размещены в директории [quick-start](quick-start). Они иллюстрируют процесс обучения моделей одним из указанных способов:

1. Напрямую из Jupyter-ноутбука, подключенного к GPU.
   
   Пример доступен по ссылке: [Обучение модели в ноутбуке с GPU](quick-start/notebooks_gpu).

2. Посредством отправки задачи обучения на кластер.

   [Обучение модели через Training Job API](quick-start/job_launch).

Дополнительные примеры обучения моделей, доступные для использования:

 * В папке [pytorch-example](pytorch-example) рассмотрен пример задачи распределенного обучения Pytorch-модели с двумя типами запуска: `horovod` (стандартный способ) и дополнительный тип запуска `pytorch` (он же `Pytorch.Distributed`).


## Предпроцессинг данных

* Загрузка/выгрузка данных на S3 в [стартовом примере](quick-start).
* [Работа с Rapids](rapids), библиотекой, ускоряющей обработку датасетов на GPU.
