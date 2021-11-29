# Ссылка на Colab
[Блокнот Python](https://colab.research.google.com/drive/1yV7iakDzJSnPO_uRZ8aAUm4ZmDpQ8Hwf?usp=sharing)

[Блокнот R](https://colab.research.google.com/drive/1Rb-YdKfJxPGgEynqQdFiXi3775fpr9Kr?usp=sharing)
# Результаты
## Анализ MultiQC
![](/img_multi/multi1.png)
![](/img_multi/multi2.png)
![](/img_multi/multi3.png)
![](/img_multi/multi4.png)
![](/img_multi/multi5.png)
## Анализ hisat и HTSeq
`__no_feature` - столько чтений соответствует участкам генома, где не аннотировано ни одного экзона

`__ambiguous` - столько чтений могут принадлежать разным генам
|ID образца|Тип образца|Все чтения|Успешно откартированные|Успешно откартированные, %|Уникально откартированные|Уникально откартированные, %|Общее число чтений, попавших на гены|
|---|---|---|---|---|---|---|---|
|SRR3414629_1|Перепрограммирование|21106089|20510113|97.18|18375888|87.06|16049609|
|SRR3414630_1|Перепрограммирование|15244711|14832680|97.30|13186139|86.50|11465324|
|SRR3414631_1|Перепрограммирование|24244069|23547686|97.13|20928945|86.33|18408851|
|SRR3414635_1|Контроль|20956475|20395865|97.32|18428317|87.94|16275997|
|SRR3414636_1|Контроль|20307147|19757059|97.29|17825380|87.78|15757580|
|SRR3414637_1|Контроль|20385570|19847291|97.36|17844858|87.54|15736978|
## Анализ DESeq2
![](/img_qual/Heat_map.png)
![](/img_qual/plotMA.png)
![](/img_qual/ncount10.png)
![](/img_qual/ncount19.png)
![](/img_qual/ncount109.png)
