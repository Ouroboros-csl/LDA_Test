## 文献计量方法
## TF-IDF

$TF_{\ t_i} = {Freq_{\ t_i}}/\ {\sum_i{Freq_{\ t_i}}}$

$IDF_{\ t_i} = {|D|}/\ {\sum_j{\ I(\ t_i\ \in\  D_j)} + 1}$

$TF-IDF_{\ t_i} = TF_{\ t_i} \* IDF_{\ t_i}$

## LDA

根据单词与文档的共现概率计算$P(W|T)$与$P(T|A)$

# 使用说明

使用前Textminer.ipynb会清除pdf_text_folder当中所有文件

## 文件夹结构
```
|-Textminer.ipynb(文本挖掘程序)
|
|-pdf_folder(储存文献pdf)
|   |
|   |-pdf.pdf
|
|-pdf_text_folder(储存文献文本内容)
|   |   
|   |-pdf.txt
|
```



