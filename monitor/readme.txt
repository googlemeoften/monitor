˵��˵����
  1.  ���Ը���tomcatId=$(ps -ef |grep java|grep -v grep |awk '{print $2}'); Ϊ�����Լ��Ľ���id�ķ���
  2.����./monitor.shʱ����cpuԤ��ֵ���������Ĭ����30����cpu����30%ʱ���ӡ�̶߳�ջ��־
  3.�߳���־���ڵ���Ϊ��λ���ļ����ڣ��ļ�������jstack[cpuֵ]-[thread16λid]-[����]_ʱ���룬��jstack0.0-2468-20160719_093714.txt
  4.crontabʵ��ÿ��һ�����monitor.sh����ؽ��̵�cpu���