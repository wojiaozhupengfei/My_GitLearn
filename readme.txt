$mkdir learngit           	����learngit�ļ���
$cd  learngit                            ת��learngit�ļ���Ŀ¼
$pwd 			��ʾ��ǰĿ¼
$git init 			ʹ��ǰĿ¼�ܿ�git����Ϊgit���Թ���Ĳֿ⣨����.git�ļ��У�

$git add readme.txt		��readme.txt�ļ��ύ��stage(�ݴ���)����û���ύ���ֿ�ķ�֧master���÷�֧��git�Զ�������
$git commit -m ''xxxx''	��stage�еĸĶ��ļ��ύ���ֿ��֧master��-m�Ǳ��θĶ���˵��
$git status 		�鿴�ֿ⵱ǰ״̬
$git diff 			�鿴�ļ��޸�����
$git diff HEAD -- readme.txt	�鿴�������Ͱ汾�������°汾readme.txt������

___ ������_____                            ___________�汾��_____________________________________
|	      |		    |        __stage________     HEAD-->____master____      |
|                     |                             |        |                      |                   |  folder           |      |
| readme.txt   |                             |        | readme.txt    |                   |  |_|                  |     |
|                     |                             |        |                      |                   |   |____file        |      |
|                     |-----git add-------|---> |                      |--commit->|   |____file        |      |
|                     |                             |        |                      |                   |      |____file     |      |
|                     |                             |        |_______________|                   |_______________|      |
|______________|                             |______________________________________________________|
                                                      
$git log			�鿴�ύ��־
$git log --pretty=oneline	����ʾ��־
$git reflog		�鿴��ʷ��־
$git reset --hard HEAD^	���˵���һ�汾
$git reset --hard HEAD^^	���˵�����һ�汾
$git reset --hard HEAD~100 	���˵�ǰ100���汾
$git reset --hard 1094a	���˵�1094a�汾

$cat readme.txt		�鿴readme.txt����
$git checkout -- readme.txt	������������readme.txt�ļ����޸�,��ʵ�����ð汾����滻��������
$git reset HEAD readme.txt	���ݴ���readme.txt���޸ĳ�����

$rm readme.txt		ɾ����������readmen.txt
$git rm readme.txt	$git commit -m "remove readme.txt"	ɾ���汾���е�readme.txt

$git remote add origin git@github.com:wojiaozhupengfei/My_LearnGit �����زֿ���github��Զ�ֿ̲������origin��Զ�̿��Ĭ�����֣������޸ģ�һ�㲻�ģ�,����wojiaozhupengfei���github�˻��е�My_LearnGit���Զ�ֿ̲�
$git push -u origin master 	�����زֿ�������������͵�Զ�ֿ̲�(master��֧���͵�github)



