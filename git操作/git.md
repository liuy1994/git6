fid = fopen(filename,'w','n','UTF-8');



����|����
----|------
gui�򿪵�ǰ·��|start .
����Ŀ¼|cd
��ʾ��ǰĿ¼|pwd
����Ŀ¼|mkdir Ŀ¼��demo
����Ŀ¼|mkdir -p Ŀ¼·��      //��demo 1/demo 11/demo 111��
--|--
�鿴·��|ls ·��
�鿴·��|ls -a ·��
�鿴·��|ls -l ·��
�鿴·��|ls -al ·��
--|--
�����ļ�|echo ��1�� > �ļ�·��  //1.txt(û�оʹ���1.txt������о͸���������)
�����ļ�|echo ��1�� >! �ļ�·�� //��������
�����ļ�|echo ��1�� >> �ļ�·�� //1.txt(������ݵ�1.txt��
�����ļ�|touch 1.txt            //��û��1.txt��
�ı��ļ�����ʱ��|touch 1.txt	//������1.txt��
�鿴�ļ�����|cat 1.txt
--|--
�����ļ�|cp Դ·�� Ŀ��·��	//cp 1.txt ../2.txt
����Ŀ¼|cp -r Դ·�� Ŀ��·��	//
�ƶ��ڵ�|mv Դ·�� Ŀ��·��	//��mv 1.txt 2.txt ��������
--|--
ɾ���ļ�|rm �ļ�·��
ǿ��ɾ���ļ�|rm -f �ļ�·��
ɾ��Ŀ¼|rm -r Ŀ¼·��
ǿ��ɾ��Ŀ¼|rm -rf Ŀ¼·��

# ����
����|����
--|--
�ص��ղŵ�Ŀ¼|cd -
ʹ����һ�ε�����|�������
ִ����һ�ε�����|����	//����
ʹ����һ�ε����һ������|alt .
һ�仰ִ����������|XXX��YYY
һ�仰ִ����������|xxx&&yyy
����Ƶ���ͷ|ctrl A
����β|ctrl E
ɾ��|ctrl D
ǰ��|ctrl F
����|ctrl B

# ��������������س���Ϊ���Ű棩 

  \�����س���������ִ������

# ����
find . -name 1.txt	//����1.txt
find . -name "demo*" -type d	//tpye��ʾ�ҵ���Ŀ¼  demo*��ʾ���к�demo��Ŀ¼����demo1 ��demo2

# vim ~/.bashrc
## 1. ʹ�� ~/.bashrc 
alias XXX=�����	//����f=��ls -a��
source ~/.bashrc	//bashrc�Ķ���Ч

## 2. ʹ�� bash ����

�� ~/.bashrc �������һ������

frank (){
echo 'frank is awesome'
}
�� bashrc ��Ч
source ~/.bashrc
���� frank ����
## 3. ��ʹ�� bashrc
���� alias frank="echo 'frank is awesome'"
���� frank


























# git clone git@github.com:liuy1994/blog.git 
# git init //��ʼ��
# git pull //�ϲ�Զ�̿⣨�����˿����޸ģ�ִ�в���ǰ���ȣ�
# git status 
# git add . //��ӵ��ݴ���
# git commit -am "add" //�ύ�����ؿ⡣��m��Ϊ��ע����˼����ע����˫�����������
# git push origin master //���͵�githubԶ�̿�
# echo "XXX" > a.md
# echo "XXX" >> a.md
# rm -rf a.md//ֱ��ɾ��a.md
