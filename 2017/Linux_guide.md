# Linux����������

## Ŀ��

���ĵ���Ҫ��Գ�����Linux�����ϲ���Ӧ�ã���Linux����ϵͳ����Ϥ�Ŀ������û����о�һЩ���õ�������Լ������裬�������߶�Linuxϵͳ��һ���������˽��ѧϰ

## ����

�Ƽ����𹤾ߣ�

�ն˹��ߣ�XShell 5

�ļ��ϴ���XFtp 

## Linux��������

- man:��������ѧϰ��������,�κ�linux�ն��������ͨ��������鿴����ѧϰ�����������ϸ���������£�

[![d](https://xiaoymin.github.io/images/2017/man.png "d")](https://xiaoymin.github.io/images/2017/man.png "d")

�س������ϸ��ʾvim����ľ���������÷�

[![d](https://xiaoymin.github.io/images/2017/man1.png "d")](https://xiaoymin.github.io/images/2017/man1.png "d")

- cd:�л��ļ����������ӵ�ǰ/homeĿ¼�л���/mntĿ¼���������£�

[![d](https://xiaoymin.github.io/images/2017/cd.png "d")](https://xiaoymin.github.io/images/2017/cd.png "d")

- pwd:��ʾ��ǰ�û������ļ���λ�ã��������£�

[![d](https://xiaoymin.github.io/images/2017/pwd.png "d")](https://xiaoymin.github.io/images/2017/pwd.png "d")

- ps:չʾ��ǰ�������飬һ�����ڲ���

��������֪����ǰlinuxϵͳ�����˶���java��صĽ��̣��������£�

	```ps-ef|grep java```
	
[![d](https://xiaoymin.github.io/images/2017/ps.png "d")](https://xiaoymin.github.io/images/2017/ps.png "d")

- netstat: ��ӡ�������ӡ�·�ɱ��ӿ�ͳ�ơ�αװ���ӺͶಥ��Ա

������һ������ͨ���˿ںŲ��ҽ��̣���������

[![d](https://xiaoymin.github.io/images/2017/netstat.png "d")](https://xiaoymin.github.io/images/2017/netstat.png "d")

- kill:��ֹ���̷���

���kill -9 pid

Pid�ǽ��̺�

[![d](https://xiaoymin.github.io/images/2017/kill.png "d")](https://xiaoymin.github.io/images/2017/kill.png "d")

- mv:�ƶ��ļ�

�����������Ϊ�ƶ��ļ����Ҳ������Ϊ��������ʹ�ã�

[![d](https://xiaoymin.github.io/images/2017/mv.png "d")](https://xiaoymin.github.io/images/2017/mv.png "d")

- mkdir�������ļ���

�������£�

[![d](https://xiaoymin.github.io/images/2017/mkdir.png "d")](https://xiaoymin.github.io/images/2017/mkdir.png "d")

- ls:չʾ�ļ���Ŀ¼�б���Ϣ

�������£�

[![d](https://xiaoymin.github.io/images/2017/ls.png "d")](https://xiaoymin.github.io/images/2017/ls.png "d")

- vim:�༭��

vim��linux һ���༭���������ϸ������ͨ��man�������������ѧϰʹ�ã����ﲻһһ�о�
��ĸi����༭״̬
��ťesc�˳��༭״̬
:wq���浱ǰ�ļ����˳�
:wq!ǿ�Ʊ��沢�˳�
:q!�������˳�

## tomcat����

����cd��tomcat��Ŀ¼��Ȼ��ִ����������

- bin/startup.sh:������ǰtomcat����
- bin/shutdown.sh:�رյ�ǰtomcat����

## nginx����

����cd��nginx��Ŀ¼��Ȼ��ִ����������
- sbin/nginx:����nginx
- sbin/nginx -s reload:����nginx
- sbin/nginx -t:����nginx�����Ƿ���ȷ���Ƿ������

## pm2����

pm2��nodejs�Ľ��̹���������ɫ������JavaӦ���е�tomcat��һ�����ǵ�nodejsӦ�ö���ͨ��node����������

���磺

[![d](https://xiaoymin.github.io/images/2017/pm2.png "d")](https://xiaoymin.github.io/images/2017/pm2.png "d")

���ַ�ʽ����˲����ʱ���Ǻ��ȶ����淶,����nodejsӦ�ò���ʹ��pm2
ͨ��pm2 help���Բ鿴��ϸ����

[![d](https://xiaoymin.github.io/images/2017/pm2_1.png "d")](https://xiaoymin.github.io/images/2017/pm2_1.png "d")

��Ҫ�������£�

[![d](https://xiaoymin.github.io/images/2017/pm2_2.png "d")](https://xiaoymin.github.io/images/2017/pm2_2.png "d")