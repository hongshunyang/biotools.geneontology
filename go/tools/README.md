# How to use

## Python Version

* 2.x

## Python Dependencies

* mysql-python

## Options

* -i <--input csv file:原始数据文件
* -g <--goda  csv file:GO子孙数据
* -c <--check csv file:BP,MF,CC既要统计合并的GOID数据
* -s <--settings csv file:配置文件
* -t <--type :goid,goterm
* -d <--desendant name prefix like BP,CC,MF


## Examples

```shell
./app.py -i ./../data/1104/BP/GO-BP-CDS.csv -s settings.conf -c BP-GOID.txt -t goid
```

```shell
./app.py -i ./../data/1104/BP/GO-BP-CDS.csv -g ./../result/BP_desendant_ancestor.csv -c BP-GOID.txt -t goid
```


