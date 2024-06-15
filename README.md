# Euglenozoa Trypanosoma Rangeli
Индвидуальная часть проекта по биоинформатике.
- [Организма на NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_003719475.1/)
- [Групповая презентация](https://docs.google.com/presentation/d/1lf8zt1BlVBf_tpJix5-Uvcekrgt4gaCcpDrAxZpYYio/edit?usp=sharing)

# Краткое описание организма
![Trypanosoma_rangeli](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_1/results/Trypanosoma_rangeli.png)

Trypanosoma rangeli — жгутиковый паразит из группы трипаносом, переносимый кровососущими клопами и инфекционный для разных млекопитающих, включая человека. Хотя не вызывает заболеваний у людей, может быть спутан с возбудителями болезни Шагаса.

Вид упоминается на PubMed в 572 публикациях, N50 равен 43,2 Кб, длина генома 21,2 Мб.

Содержит 10 589 генов, из которых 10 104 кодируют белки.


# Data
Ввжно отметить, что все входные данные, а также результаты хранятся на этих двух дисках (помимо того, что есть в текущем репозитории):
+ [Диск 1](https://drive.google.com/drive/folders/1rPpQoxnD5I5c8rjcTnZNXJNRCykSyKmd?usp=sharing)
+ [Диск 2](https://drive.google.com/drive/folders/1f9j8_TV8seq5vaY7jbuJ7LYNxbRUEc3Q?usp=sharing)
+ Файлы с кодом включены в данный репозиторий
  
# Результаты
Промжетуочные результаты получались на каждом шагу - bed файлы, выравненные последовательности таблицы и так далее. Попробую кратко пройтись по ключевому.

## Распределение структур по геному
Для наглядности результаты представлены в виде таблицы

Участок | Число квадруплексов | Доля квадруплексов | Число предсказаний Zhunt | Доля предсказаний Zhunt | Число предсказаний ZDNABERT | Доля предсказаний ZDNABERT
--- | --- | --- | --- | --- | --- | --- 
Exons | 449 | 18,22% | 9720 | 66,42% | 15400 | 55,14%
Promoters | 1863 | 75,60% | 13729 | 93,82% | 25071 | 89,77%
Downstream | 930 | 37,74% | 10880 | 74,36% | 18127 | 64,90%
Introns | 1865 | 75,69% | 14119 | 96,49% | 22604 | 80,94%
Intergenic | 1865 | 75,69% | 14119 | 96,49% | 22604 | 80,94%

## Результаты выравнивания через LocARNA
+ [Выравненные последовательности через LocARNA](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/LocARNA/input.out/results/result.aln)
+ [LocARNA](http://www.bioinf.uni-freiburg.de/Software/LocARNA/)

А также:

![Image](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/aln.png)

Также было сделано выравнивание через [muscle](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/atpaseBeta.fas)
![Image](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/muscle.png)

Собственно и сами последовательность изначальные [genes_2.fa](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/genes_2.fa)

## Bed
Не все сохранились файлы, но например остались 
+ [bed_predictions.bed](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/bed_predictions.bed)
+ [genomic.bed](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/genomic.bed)
+ [prom_gen.bed](https://github.com/HpPpL/bioinformatics-project/blob/main/chapter_3/results/prom_gen.bed)
+ [pqs.bed](https://drive.google.com/file/d/1kYjasU9ZfelEpG98P4R-g8zCAfEqhhjr/view?usp=drive_link)


## Свёртка в структуры
Ну и групповые результаты проекта по сверткам:
