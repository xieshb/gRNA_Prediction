# gRNA_Prediction
Predicting gRNA for target gene or fragment in genome.

程序文件目录：


bin

    ├── DNA.jpg
  
    ├── Get_Gene_info_genbank.exe
    
    ├── bowtie-align-l.exe
  
    ├── bowtie-build-l.exe
  
    ├── chopchop.exe
  
    ├── gRNA_GUI.exe
  
    ├── gRNA_Prediction.exe
  
    └── src

程序文件说明

bin目录中的文件要保持在同一目录中。

DNA.jpg 是帮助框旁边的背景缩图

Get_Gene_info_genbank是处理genbank文件获取坐标及序列信息的程序

bowtie-align-l 是bowtie比对程序

bowtie-build-l是建立bowtie index索引程序

chopchop是预测gRNA的主程序

gRNA_GUI 是 GUI界面程序，双击即可打开用户界面

gRNA_Prediction 是出来GUI界面参数及chochop预测结果的主程序

src 是primer3的依赖库文件


详细参数和输入文件说明见：gRNA_Prediction-使用说明-20220728.pdf
