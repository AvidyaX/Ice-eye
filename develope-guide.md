# ���ݿ�
  ����Ŀ����mysql���ݿ⣬��Ҫ���ذ�װmysql������iceeye��database���û���Ϊiceeye������Ϊ123456����ʼ���ű�λ��doc\install\initsql.sql�

# Ice web���̱�������

���̲�����spring-boot������򻯿����Ͳ�������Դ�빤�̣�Ȼ��
��eclipse�е���maven��Ŀ��ִ��Run As����> Maven Build�����ɱ���Դ�룬����ɹ��Ժ���targetĿ¼��������all in one��JAR��ice-eye-web-xxxxx.jar,���������������⣬���������� java -jar ice-eye-web-xxxxx.jar��������Web����������������http://localhost:8080���ɷ��ʡ�
eclipse�е����ʱ������Run As����>Java Application��������Web��
��Ŀ��������JDK 7��

## ����Ŀ¼˵��
src\mainĿ¼Ϊ��ҪԴ��
src\testĿ¼Ϊ����Դ�룬��ҪΪ��Ԫ����
src\mainĿ¼�����°��ṹ��

 - io.mycat.ice.domainĿ¼Ϊ����������Щ������Ӧmysql���ݿ����һ����
 - io.mycat.ice.bean��Ϊ����Java Bean�����������ݴ��ݻ�ת����Ŀ��
 - io.mycat.ice.rest��Ϊ�ṩRest�����Java������������ڲ����ⲿϵͳ����
 - io.mycat.ice.ctrl��ΪSpring MVC��Controller�������ڵط�
 - io.mycat.ice.service��ΪSpring��Service Bean�������ڵط�
 ����ctrl����service�����԰���ģ�����Ʒ��Ӱ�������io.mycat.ice.ctrl.install.xxx

ҳ���ļ�����̬��JSP��JS��Images�ȣ���������Ŀ¼
 - src\main\resources\static  ��Web������ROOTĿ¼