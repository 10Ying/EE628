环境：
python 3.5
packages:
	tensorflow,keras,numpy,pandas,os(内置),shutil(内置)，time(内置)

Note: 数据较大,非笔记本NVIDA显卡建议用tensorflow-gpu加速，笔记本就不要折腾了烧显卡。

文件说明：
1_New folder & Copy images：用来创建文件夹，复制并分类图片，为读取数据做稳准
2_simple cnn try 一个简单的cnn模型直接run的实验，有完整的数据准备，模型，预测部分，方便保留数据和预测部分，只需修改模型，参数来调整模型。
prediction.csv:程序自动储存的预测文件，这部分算法没有弄清楚先写上完整程序，清楚再改，就给你们看看样子不用管
log.docx: 用来记录每次用于提升准确率的参数调整，和结果。记录下来方便些report
Note:两个程序的完成均参考http://keras-cn-docs.readthedocs.io/zh_CN/latest/blog/image_classification_using_very_little_data/，不清楚或者有什么bug可以问我或者看这个网址

阶段目标：
1.准备好数据（run好1_New folder & Copy images）
2.测试一下完整的从数据到简单模型到预测的代码（run好2_simple cnn try）
3.自己调整参数尝试提高准确率，并把结果记录在log中
4.尝试建立fine-tune模型，参考：
http://keras-cn-docs.readthedocs.io/zh_CN/latest/blog/image_classification_using_very_little_data/





1_New folder & Copy images：

Step1：找到准备放数据的文件夹，修改path路径
Step2：run，#如果存放文件夹的位置已有data文件夹，会提示文件夹已经存在，可以改名或者换文件夹，或者更换代码中的“data”

2_simple cnn try
Step1：修改path路径
Step2：调整参数，验证代码完整性，第一次实验建议把epochs设为1加快速度。
Step3：根据结果调参，记录模型summary，loss，accuracy,validation accuracy到“log.docx”