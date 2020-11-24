# EC2loginwithPassword

1.cd /etc/ssh/sshd_config


2.remove # from below line
PasswordAuthentication yes

3. Provide password to the ec2-user
   passwd ec2-user

4.  restart the sshd

systemctl stop sshd
systemctl start sshd

