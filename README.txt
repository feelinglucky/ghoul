Ghoul - Simple MiniBlog

Ghoul Ϊʹ�� Sqlite �ļ�΢����ϵͳ

=����=

    1��ʹ�� HTTP ��֤
    2���Զ��������ļ���data/config.ini��
    3�������ⲿ API ����
    4��ʹ�� Apache ��д URL �Ѻ�
    5�����в��ϵͳ������ͬ������������΢����ϵͳ 


=ϵͳ����=

    1��PHP5 ���ϣ���Ҫ PDO_Sqlite ֧��
    2��Apache ֧�� .htaccess �ļ��Լ��� mod_rewrite ģ��


=��װ=

    1������װ����ѹ����ĳ Apache �ɷ���·��
    2����������������༭ data/config.ini �����ļ�
    3���� *ix �У��� data Ŀ¼����Ϊ 777
    4������ install.php ����������������ɾ��


=API=

    �������У�Ghoul ��װ�� http://127.0.0.1/micro_blog/ ��ô

    ==���ͣ���ȷ�������������ݿ� ID��==

        http://127.0.0.1/micro_blog/post

        ������content ��������
        ��֤����Ҫ HTTP ��֤

    ==��ȡ��JSON ��ʽ��==

        ===������Ŀ===

            http://127.0.0.1/micro_blog/show/?ajax=true

        ===ָ�� ID ����Ŀ===

            http://127.0.0.1/micro_blog/show/[id]/?ajax=true

            ע���� data/config.ini �������� AUTH_OBTRUSION = true ʱ����Ҫ HTTP ��֤

    ==ɾ������ȷ�������������ݿ� ID��==

        http://127.0.0.1/micro_blog/delete/[id]/

        ����

        http://127.0.0.1/micro_blog/delete?id=[id]

        ��֤����Ҫ HTTP ��֤


=��ϵ��ʽ=

    mingcheng<i.feelinglucky[at]gmail.com>
    Blog: http://www.gracecode.com/
