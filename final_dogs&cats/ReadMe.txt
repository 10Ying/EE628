������
python 3.5
packages:
	tensorflow,keras,numpy,pandas,os(����),shutil(����)��time(����)

Note: ���ݽϴ�,�ǱʼǱ�NVIDA�Կ�������tensorflow-gpu���٣��ʼǱ��Ͳ�Ҫ���������Կ���

�ļ�˵����
1_New folder & Copy images�����������ļ��У����Ʋ�����ͼƬ��Ϊ��ȡ��������׼
2_simple cnn try һ���򵥵�cnnģ��ֱ��run��ʵ�飬������������׼����ģ�ͣ�Ԥ�ⲿ�֣����㱣�����ݺ�Ԥ�ⲿ�֣�ֻ���޸�ģ�ͣ�����������ģ�͡�
prediction.csv:�����Զ������Ԥ���ļ����ⲿ���㷨û��Ū�����д��������������ٸģ��͸����ǿ������Ӳ��ù�
log.docx: ������¼ÿ����������׼ȷ�ʵĲ����������ͽ������¼��������Щreport
Note:�����������ɾ��ο�http://keras-cn-docs.readthedocs.io/zh_CN/latest/blog/image_classification_using_very_little_data/�������������ʲôbug�������һ��߿������ַ

�׶�Ŀ�꣺
1.׼�������ݣ�run��1_New folder & Copy images��
2.����һ�������Ĵ����ݵ���ģ�͵�Ԥ��Ĵ��루run��2_simple cnn try��
3.�Լ����������������׼ȷ�ʣ����ѽ����¼��log��
4.���Խ���fine-tuneģ�ͣ��ο���
http://keras-cn-docs.readthedocs.io/zh_CN/latest/blog/image_classification_using_very_little_data/





1_New folder & Copy images��

Step1���ҵ�׼�������ݵ��ļ��У��޸�path·��
Step2��run��#�������ļ��е�λ������data�ļ��У�����ʾ�ļ����Ѿ����ڣ����Ը������߻��ļ��У����߸��������еġ�data��

2_simple cnn try
Step1���޸�path·��
Step2��������������֤���������ԣ���һ��ʵ�齨���epochs��Ϊ1�ӿ��ٶȡ�
Step3�����ݽ�����Σ���¼ģ��summary��loss��accuracy,validation accuracy����log.docx��