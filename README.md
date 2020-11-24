# EC2loginwithPassword

cd /etc/ssh/sshd_config


removed the #
PasswordAuthentication yes

restart the sshd

systemctl stop sshd
systemctl start sshd

