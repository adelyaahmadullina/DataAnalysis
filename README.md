# DataAnalysis
Разработка системы обнаружения аномалий в промышленных процессах на основе данных датчиков.

[Данные, нужные для запуска кода](#title1)

[Запуск кода](#title2)

[Как работает код](#title3)

[Результат работы кода](#title4)

## <a id="title1">Данные, нужные для запуска кода</a>
Техн_интеллект_анализа_данных_Ахмадуллина.ipynb - основная программа   
Датасет [TrainingDataConveyor.csv](https://drive.google.com/file/d/1HqUO4eOKcOItfD1ZkWzChXX-CIS5HmB-/view?usp=drive_link)

## <a id="title2">Запуск кода</a>
Загрузите  [TrainingDataConveyor.csv](https://drive.google.com/file/d/1HqUO4eOKcOItfD1ZkWzChXX-CIS5HmB-/view?usp=drive_link) в Google Colab  
<img width="211" alt="image" src="https://github.com/adelyaahmadullina/DataAnalysis/assets/120652605/47d8af81-5bb6-419a-9f5f-4458c7352bf0">

После этого запустите код. После выполнения всего кода, у нас появится результат. <img width="332" alt="image" src="https://github.com/adelyaahmadullina/DataAnalysis/assets/120652605/7425e89e-9abb-4d76-8556-76a4b4bcbb1b">

## <a id="title3">Как работает код</a>
Этот код выполняет задачу анализа данных и построения модели классификации на основе Isolation Forest для разработки системы обнаружения аномалий в промышленности. Загружаются необходимые библиотеки для работы с данными, построения модели и визуализации. Данные с датчиков считываются из CSV-файла. Выделяются функции (признаки) и целевая переменная из данных. Данные разделяются на обучающий и тестовый наборы для оценки производительности модели. Создается и обучается модель Isolation Forest на обучающих данных. Модель применяется к тестовым данным для получения предсказаний. Проводится оценка производительности, при условии, что все являются нормальными.  Выводится результат.


## <a id="title4">Результат работы кода</a>
<img width="332" alt="image" src="https://github.com/adelyaahmadullina/DataAnalysis/assets/120652605/7425e89e-9abb-4d76-8556-76a4b4bcbb1b">
