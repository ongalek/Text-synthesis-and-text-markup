

# Text-synthesis-and-text-markup

Данная репозиторий создан в рамках работы ВКР 2023г "Разработка алгоритма для синтеза и разметки речи"

## Speech synthesis

Данный раздел посвящен синтезу речи на основе полученных в ходе работы с разделом Text Markup обучающих данных моделей tacotron2 и waveglow.
### Пример использования

```cmd
python train.py
```


## TextMarkup

Text Markup - в данном разделе находится полноценный алгоритм для создания транскрипций(разметки речи) на основе ASR модели Google Clouda ASR,
с последующим полноценным созданием датасета

### Пример использования

Для запуска необходимо последовательно щапустить ячейки файла ASR dataset collecting algorithm, убедитесь, что установлено requirements.txt

## Converting algorithm 

Для работы Tacotron 2 необходимо устанвоить нужное число каналов и выбрать необходимый формат данных, для этих целей создан отдельный алгоритм, позволяющий осуществвлятиь данные процедуры


## Контакты

iksmolenchuk@edu.hse.ru - researcher

manizhegorodov@edu.hse.ru - researcher

mpselin@edu.hse.ru - project manager/ tester

