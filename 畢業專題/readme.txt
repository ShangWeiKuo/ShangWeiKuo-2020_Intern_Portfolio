system     : CentOS 7 
web        : ngimx+php-fpm 
ftp        : vsftpd
firewall   : iptables+fail2ban 
BD         : MySQL
Repository : Remi


��l�ɮפ�SQL�ϥΤ��b���K�X 

FTP
    username: admin
    password: BZ76agROZh

SQL
    username: root
    password: BZ76agROZh



AllPass �����޲z���b���K�X


SQL
    username: admin
    password: BZ76agROZh



�b���b��CentOS 7�U�ϥΥH�UVestaCP�}�����O�f������



# Connect to your server as root via SSH
ssh root@your.server

# Download installation script
curl -O http://vestacp.com/pub/vst-install.sh

# Run it
bash vst-install.sh --nginx yes --phpfpm yes --apache no --named no --remi yes --vsftpd yes --proftpd no --iptables yes --fail2ban yes --quota no --exim no --dovecot no --spamassassin no --clamav no --softaculous yes --mysql yes --postgresql no


FTP/SQL�b���K�X : �̷Ӧw�˸}���i��]�m


1.�n�J http://IP/phpmyadmin  �פJsql

2.�i�Jhttp://IP:8083 �n�J�Ыغ����ؿ��A�H��SSL�]�m(�Y���j�w��W)

3.�ϥ�ftp�i�J�����ؿ��öפJ�����ɮ�

--

�iPHP�j

index.php			����

answer*.php			���ݩ���ש��U���d���B�z����
backend*.php			�޲z����x�Ϫ����
class-info.php			�ҵ{��T����
class-list.php			�ҵ{�C����
comment*.php			���׳B�z�����]��m�^
doAction.php, upload*.php	�ɮפW��
edit-member.php			�ק�|�����
favofite*.php			�ڪ��̷R�B�z����
homework*.php			�ɮפW�ǳB�z����
member-page.php			�ڪ��̷R����
pythoninphp*.php		��x���R�B�z����
question*.php			���׳B�z����
register*.php			���U�B�z����
reset*.php			���]�K�X�B�z����
score-send.php			�����B�z����
tabpic*.php			��x�Ϫ����
teacher-info.php		�H�Юv�W�ٷj�M������
verify.php			�{�ҳB�z����

content/			���O���ɦW���ڥؿ����������]�ˤ����e

function/do-login.php		�n�J�B�z����
function/do-logout.php		�n�X�B�z����
function/pw-hash.php		�K�X����B�⭶��
function/token.php		�\�i�q��X���ͭ���

part/backend*.php		��x���������ե�
part/footer.php			�����������s�i��
part/header.php			�����������j�M���
part/nav.php			�j�M��Ϥ��e�w�q
part/sidebar*.php		����
part/sql-connection.php		��Ʈw�s�u
