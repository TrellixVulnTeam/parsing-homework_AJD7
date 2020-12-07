### Домашнее задание по разделу "Синтаксис" по курсу "Продвинутые задачи и модели NLP"

В репозитории 3 ноутбука: 2 с домашним заданием для каждого парсера и 1 с решением задач с семинара.

### Домашняя работа

**parser_shkunkov** - ноутбук с обучением и тестом парсера составляющих
Результаты для тестовых данных:

`Loading test trees from data/test_con.txt...`<br/>
`Loaded 2,416 test examples.`<br/>
`Loading model from models/en_bert_dev=95.22.pt...`<br/>
`Parsing test sentences...`<br/>
`test-fscore (Recall=94.93, Precision=95.71, FScore=95.32, CompleteMatch=52.24) test-elapsed 0h00m46s`<br/>

F-мера > 0.95

dependency_parser_shkunkov - ноутбук с обучением и тестом парсера зависимостей
Результаты для тестовых данных: 

`Reading dependency parsing data from data/test_dep.txt`<br/>
`Loading test trees from data/test_con.txt...`<br/>
`Loaded 2,416 test examples.`<br/>
`Parsing test sentences...`<br/>
`test-fscore (Recall=94.93, Precision=95.23, FScore=95.08) test-elapsed 0h01m00s`<br/>
`best test W. Punct: ucorr: 54536, lcorr: 53529, total: 56684, uas: 96.21%, las: 94.43%, ucm: 64.53%, lcm: 48.59%`<br/>
`best test Wo Punct: ucorr: 48220, lcorr: 47217, total: 49893, uas: 96.65%, las: 94.64%, ucm: 67.38%, lcm: 50.58% `<br/>
`best test Root: corr: 2370, total: 2416, acc: 98.10%`<br/>

UAS > 0.96

### Семинар
seminar-shkunkov - решенный семинарский ноутбук