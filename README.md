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
|ID экземпляра|Тип|Все чтения|Уникально картированные|__no_feature|__ambiguous|Общее число чтений, соответствующих хотя бы одному гену|
|---|---|---|---|---|---|---|
|SRR3414629_1|Перепрограммирование|21106089|18375888|1604107|722172|16049609|
|SRR3414630_1|Перепрограммирование|15244711|13186139|1240295|480520|11465324|
|SRR3414631_1|Перепрограммирование|24244069|20928945|1700354|819740|18408851|
|SRR3414635_1|Контроль|20956475|18428317|1392186|760134|16275997|
|SRR3414636_1|Контроль|20307147|17825380|1332692|735108|15757580|
|SRR3414637_1|Контроль|20385570|17844858|1397650|710230|15736978|
## Анализ DESeq2
![](/img_multi/Heat_map.png)
![](/img_multi/plotMA.png)
![](/img_multi/ncount10.png)
![](/img_multi/ncount19.png)
![](/img_multi/ncount109.png)
